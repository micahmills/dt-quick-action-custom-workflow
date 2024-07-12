![Build Status](https://github.com/DiscipleTools/dt-quick-action-custom-workflow/actions/workflows/ci.yml/badge.svg?branch=master)
## readme format:

![Plugin Banner](https://raw.githubusercontent.com/DiscipleTools/dt-quick-action-custom-workflow/master/documentation/banner.png)

# Disciple.Tools - Quick Action Custom Workflow
This Plugin allows you to create custom workflows for quick actions in Disciple.Tools.


## Purpose

You can now augment the value of a quick action field based on the value of another field. This is helpful if you want to count meetings or other activities based in a magic link where the quick action button is not available.

## Usage

To Use this plugin you must have the Disciple.Tools Theme installed on a Wordpress Server. You can then create a custom field or use an existing field to trigger the quick action in a workflow. Create a new workflow where Step 1 is looking for a field updated, Step 2: select he field you want to watch and the value you want to watch for. Step 3: Select your quick action field (ie. Meeting Scheduled) and from action select 'Custom Action', from the value drop down select 'Add To Quick Action Field Value.' Step 4 give you workflow a name and save it.

Now when the field you selected in step 2 is updated to the value you selected, the quick action field will be updated with the value you selected in step 3.

#### Will Do

- Update a value in a quick action field based on the value of another field.

#### Will Not Do

- Create a new quick action field.
- Create a new field to watch for changes.

## Requirements

- Disciple.Tools Theme installed on a Wordpress Server

## Installing

- Install as a standard Disciple.Tools/Wordpress plugin in the system Admin/Plugins area.
- Requires the user role of Administrator.
