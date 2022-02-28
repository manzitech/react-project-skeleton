## Components

In this folder, you add global shared/reusable components. You can group different files depending on their types. The first group might common folder where you can add header, footer and other. You can also have a folder for Form and add TextFields and others components you might to create a form.

Below is a tree example of how this folder might look

    /Components
        ├── /Forms
        │   ├── /TextField
        │   │   ├── TextField.js
        │   │   ├── TextField.styles.js
        │   │   ├── TextField.test.js
        │   │   └── TextField.stories.js
        │   ├── /Select
        │   │   ├── Select.js
        │   │   ├── Select.styles.js
        │   │   ├── Select.test.js
        │   │   └── Select.stories.js
        ├── /Common
        │   │   ├── Header.js
        │   │   ├── Footer.js