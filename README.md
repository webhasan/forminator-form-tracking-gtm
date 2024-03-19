# Forminator Form Tracking with Google Tag Manager
## User inputs included (name, email, phone number, etc) which is required for enhance conversion tracking

[Video Tutorial 🔴 ▶️](https://youtu.be/JEtaWux-Jds)

### How to use 
1. In Google Tag Manager, create a new tag as a custom HTML tag.
2. Inside the tag, paste the entire code from the `forminator-form-datalayer.html` file provided in this repository. 
3. Set the trigger to fire on All Pages page views.

Once you've configured this setup, you'll begin receiving Google Tag Manager dataLayer events as `forminator_form_submit`. You will get form ID as ***form_id*** and all other form inputs as ***inputs*** object.

