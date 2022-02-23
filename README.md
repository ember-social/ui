# Ember UI

Ember UI is a React UI library..

[View Supabase Root Docs](https://ui.supabase.com)
.
## Install Ember UI

```cli
npm install @ember-social/ui
```

## Using Ember UI

Example of importing a component

```js
import { Button } from '@ember-social/ui'

//...

return <Button>I am a Supabase UI button</Button>
```

It is probably advisable to use [Normalize](https://github.com/sindresorhus/modern-normalize) with Supabase UI for the timebeing.

## Using Icons

We use [Feather icon library](https://feathericons.com/) in Ember UI

You can use any Icon from the library as a component by prepending `Icon` to any Icon name, like, `<IconMail>`

```js
import { IconMail } from '@ember-social/ui'

//...

return <IconMail size="small" />
```


## Scope

Some of these are a work in progress - to be developed by @supabase/ui.

_General_

- [x] Button
- [x] Typography
- [x] Icon
- [x] Image (work in progress)

_Data Input_

- [x] Input
- [x] InputNumber
- [x] Select (custom select wip)
- [x] Checkbox
- [x] Radio
- [x] Toggle
- [ ] Upload
- [ ] Slider
- [ ] Date picker
- [ ] Time picker
- [ ] Form

_Layout_

- [ ] ~~Layout~~
- [ ] ~~Grid (Flex)~~
- [x] Divider
- [x] Space (Flex)

_Display_

- [x] Card
- [ ] Avatar
- [x] Accordion
- [x] Alert
- [x] Badge
- [x] Menu
- [ ] Tooltips
- [ ] Tables
- [ ] Code block

_Navigation_

- [x] Tabs
- [ ] Breadcrumb
- [x] Dropdown
- [x] Menu
- [ ] Page Header
- [ ] Sidebar
- [ ] Flyout menu
- [ ] Steps

_Overlay_

- [x] Modal
- [x] Context Menu
- [x] Drawer / SidePanel
- [ ] Toast messages / Notification
- [ ] Progress
- [ ] Feeds / Timeline

_Utility_

- [x] Loading
- [x] Transition (work in progress)

_Misc_

- [x] Storybook docs
- [ ] Theming (in progress)
- [x] Supabase Auth Elements
- [x] Documentation website

