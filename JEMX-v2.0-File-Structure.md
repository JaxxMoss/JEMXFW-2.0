# File structure

## [SCSS]

- ### [base] 
  - #### [content]
    - **_body.scss**
    `Selectors: body`
    - **_formatting.scss**
    `Selectors: h1-h6, p, span, strong, em, mark, del, ins, small, blockquote, q, sup, sub`
    - **_lists.scss**
    `Selectors: ul, ol, li, dl, dt, dd`
    - **_phrase.scss**
    `Selectors: abbr, code, dfn, kbd, var, pre`
    - **_semantic.scss**
    `Selectors: address, details, summary, cite`
    - **_table.scss**
    `Selectors: table, thead, tbody, tfoot, caption, tr, th, td`
    
  - #### [form]
    - **_button.scss**
    `Selectors: input, button, [type="submit"], [type="reset"]`
    - **_checks.scss**
    `Selectors: input, [type="radio"], [type="checkbox"]`
    - **_fieldset.scss**
    `Selectors: fieldset, legend`
    - **_form.scss**
    `Selectors: form`
    - **_input.scss**
    `Selectors: input`
    - **_label.scss**
    `Selectors: label`
    - **_selects.scss**
    `Selectors: select, optgroup, option`
    - **_textarea.scss**
    `Selectors: textarea`
    - *More will be added*

  - **_content.scss**
  - **_form.scss**
  - **_page.scss**
  `Selectors: html, body`
  

_Only tag, attribute and descendant selectors._
_Base styling, fonts, sizing (preferably only width), spacing and border (Only in form)._

---

- ### [config]
  - **_base.scss**
  - **_layout.scss**
  - **_state.scss**
  - **_theme.scss**

_Config maps with framework variables._
_No selectors. Only maps and functions._
_All variables that are used more than once should be stored here._

---

- ### [layout]
  - **_article.scss**
  `Selectors: article`
  - **_container.scss**
  `Selectors: .container, .container-fluid`
  - **_flex-grid.scss**
  `Selectors: .row, .col`
  - **_flex-options.scss**
  `Selectors: ai-#, `
  - **_spacer.scss**
  `Selectors: .p-$, .m-$`
  - *_header.scss*
  - *_aside.scss*
  - *_footer.scss*
  - *_section.scss*
  - *_main.scss*

_Class selectors should be used. Tag selectors can be used, but should also be made into a class._
_Only positioning, behaviour, sizing and spacing._

---

- ### [module]
  - **_alert.scss**
  `Selectors: .alert`
  - **_button.scss**
  `Selectors: .button`
  - **_card.scss**
  `Selectors: .card`
  - **_formcontrol.scss**
  `Selectors: .formcontrol`
  - **_navbar.scss**
  `Selectors: .navbar`
  - __carousel.scss_
  - __masthead.scss_
  - __notification.scss_

_Class selectors should be used. Tag selectors can be used, but should also be made into a class._
_Only positioning, behaviour, sizing, spacing and fonts_
_Colors should omitted on templating modules. Should be styled in theme_
_State colors can be used._

---

- ### [state]
  - **_message.scss**
  `Selectors: -success, -warning, -danger, -info, -emphasis`
  - **_pseudo.scss**
  `Selectors: `
  - **_visibility.scss**
  `Selectors: .is-hidden, .is-visible, .opacity-$, .sr-only`

_Class and pseudo selectors only!_
_!important may be used to force state styling_

- #### [theme]
  - **_theme-base.scss**
  - **_theme-colors.scss**
  - **_theme-layout.scss**

---

**all.scss**
`Selectors: `
**base.scss**
`Selectors: `
**layout.scss**
`Selectors: `
**module.scss**
`Selectors: `
**state.scss**
`Selectors: `
**theme.scss**
`Selectors: `
