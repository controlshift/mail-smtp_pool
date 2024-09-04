# Important Note

This repository is an exact clone of Gitlab's [mail-smtp_tool gem directory](https://gitlab.com/gitlab-org/gitlab/-/tree/master/vendor/gems/mail-smtp_pool). We only _fork_ it to be able to include the gem without cloning the entire repository (which includes a lot of unneeded code and is pretty large) with bundler.

## To update with the upstream repository

Simply clone https://gitlab.com/gitlab-org/gitlab and copy the entire `/vendor/gems/mail-smtp_pool` subdirectory here, overwriting all files. The `.gitlab-ci.yml` file can be skipped since we don't run the CI on Gitlab.
