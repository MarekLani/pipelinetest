# Notify repo owners about certain files being changed
This repo contains [example pipeline](./.github/workflows/change-notify.yml) which monitors, if certain "guarded" files has been changed by oncoming PR. If so, it automatically assigns predefined reviewer and sends email notification.

It makes use of following actions: 
- [Auto Assign Reviewer By File](https://github.com/shufo/auto-assign-reviewer-by-files)
- [Get Current Pull Request](https://github.com/marketplace/actions/get-current-pull-request)
- [Send Email](https://github.com/marketplace/actions/send-email)
