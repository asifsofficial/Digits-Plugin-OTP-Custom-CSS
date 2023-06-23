# Digits Plugin OTP Custom CSS

## Global custom CSS
```
/* Digits Custom CSS Start */
.dig_billing_wc_dv input[type=submit] {
    color: white !important;
    background-color: rgb(72,118,202) !important;
    border-radius: 25px !important;
}

.digits-form_input input, .digits-form_input input[type=text] {
    height: var(--wd-form-height);
    border-radius: var(--wd-form-brd-radius);
}

.digits-form_tab-bar .digits-form_tab-item {
		display: block;
		font-size: 15px !important;
		color: var(--wd-title-color);
    vertical-align: middle;
    font-weight: 400 !important;
		border-bottom: 1px solid rgb(130,36,227);
    padding-bottom: 0px;
}

.digits_secure_modal form {
    margin: 0;
    padding: 0;
    padding: 15px !important;
    background: white;
    border-radius: var(--wd-brd-radius);
    text-align: center;
}

.digits-form_button, .digits-form_button[type=submit] {
    background-color: var(--btn-default-bgcolor);
    color: var(--btn-default-color);
		border-radius: var(--btn-default-brd-radius);
		height: 40px;
}

.dig_popmessage_contents .dig_lasele div {
    display: block;
    color: black;
}

.digits_password_eye {
   top: 10px;
   opacity: 1;
}

.digits_password_eye-closed-line {
    background: rgb(119,119,119);
}

.digits_secure_close-sic, .digits_secure_modal-close {
    background-color: white;
    border-radius: inherit;
}

.digits-form_button-text {
    font-size: 15px;
    font-weight: 400;
}
```
## CSS for tablet
```
.wd-social-login{
flex-wrap: nowrap !important;
}
```
## Custom CSS for mobile landscape
```.wd-social-login{
flex-wrap: nowrap !important;
}
```
