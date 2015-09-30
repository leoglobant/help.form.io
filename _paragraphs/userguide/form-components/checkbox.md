---
title: Check Box
book: userguide
chapter: form-components
slug: checkbox
weight: 110
---

A check box is a boolean value input field. It will either be on or off.

![](/assets/img/checkbox-display.png)

#### Label

The label for this field that will appear next to it.

#### Protected

If checked, this field is for input only. When being queried by the API it will not appear in the properties. You can still see the value on form.io by going to the submissions for a form.

#### Persistent

If checked, the field will be stored in the database. If you want a field to not save, uncheck this box. This is useful for fields like password validation that shouldn't save.

#### Table View

If checked, this value will show up in the table view of the submissions list.

![](/assets/img/checkbox-validation.png)

#### Required

If checked, the field will be required to be checked. If it is required, you may not need to persist the value as it can be assumed to be checked when a form was submitted or it will not submit.
