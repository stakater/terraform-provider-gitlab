---
layout: "gitlab"
page_title: "GitLab: gitlab_pipeline_trigger"
sidebar_current: "docs-gitlab-resource-pipeline-trigger"
description: |-
  Creates and manages pipeline triggers for GitLab projects
---

# gitlab\_pipeline\_trigger

This resource allows you to create and manage pipeline triggers

## Example Usage

```hcl
resource "gitlab_pipeline_trigger" "example" {
   project   = "12345"
   description = "Used to trigger builds"
}
```

## Argument Reference

The following arguments are supported:

* `project` - (Required, string) The name or id of the project to add the trigger to.

* `description` - (Required, string) The description of the pipeline trigger.
