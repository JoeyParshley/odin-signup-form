# odin-signup-form

## Introduction

Create an signup form for an imaginary service to practice.

## Assignment

### Step 1: Set up and planning

1. set up git
2. set up HTML and CSS with dummy content
3. Download the [design file](https://cdn.statically.io/gh/TheOdinProject/curriculum/afdbabfab03fbc34783c6b6f3920aba4a4d3b935/intermediate_html_css/forms/project_sign_up_form/imgs/sign-up-form.png)

### Step 2: Gather Assets

1. Download background image from [unsplash.com](https://unsplash.com/photos/green-leaf-plant-in-close-up-photography-25xggax4bSA)
2. Pick an external font for the 'logo' section. [Norse Bold](https://cdn.statically.io/gh/TheOdinProject/theodinproject/efdc2888072f409e687d31dc580595dbe4fe0ff4/app/assets/fonts/Norse-Bold.otf)
3. Get image-sidebar: [Odin Log](https://cdn.statically.io/gh/TheOdinProject/curriculum/5f37d43908ef92499e95a9b90fc3cc291a95014c/html_css/project-sign-up-form/odin-lined.png)

### Step 3. Some Tips

1. Begin by scaffolding out the structure of the page, and then tackle sections one by one.
2. The area behind the “ODIN” logo is a div that has a dark, but semi-transparent background color. This enhances the readability of the text against the busy background image.
3. Color for 'Create Account' button is `#596D48`
4. The inputs, by default have a very light border (`#E5E7EB`), there are 2 variations.
   - For starters, the password inputs should have a red border if they contain an invalid password. This can be handled with the `:invalid` pseudo-class.
5. The other variation is the selected input, which should have a blue border and subtle box-shadow. This can be done with the :focus pseudo-class
6. Validating that the password fields match each other requires JavaScript. Using JavaScript to validate forms is covered in a future lesson. For now, just validate each field separately.
