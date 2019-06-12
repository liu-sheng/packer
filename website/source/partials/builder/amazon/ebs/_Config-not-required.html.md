<!-- Code generated from the comments of the Config struct in builder/amazon/ebs/builder.go; DO NOT EDIT MANUALLY -->

-   `run_volume_tags` (awscommon.TagMap) - Tags to apply to the volumes that are *launched* to create the AMI.
    These tags are *not* applied to the resulting AMI unless they're
    duplicated in `tags`. This is a [template
    engine](/docs/templates/engine.html), see [Build template
    data](#build-template-data) for more information.
    