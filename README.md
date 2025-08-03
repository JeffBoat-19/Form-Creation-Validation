# Form-Creation-Validation

 How It Works When the user clicks "Submit", the form’s default behavior is stopped with event.preventDefault().

The script checks:

If username has at least 3 characters.

If email includes both @ and ..

If password is at least 8 characters long.

Appropriate feedback messages are shown:

Green check icon for valid input

Red cross icon for invalid input

Validation Rules Field Rule Example Username Minimum 3 characters john  Email Must contain @ and . symbols me@gmail.com  Password Minimum 8 characters secure123 

Logic Flow Summary Grab the input values using getElementById.

Trim whitespace from values to prevent blank inputs.

Validate each field separately.

Use messages.push() to collect feedback.

If all fields pass (isValid stays true), allow form submission.

Otherwise, display helpful error messages.