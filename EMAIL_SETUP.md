# Email Setup Instructions

## How the Email System Works

The contact and booking forms are now configured to send emails to **rkimenyi2023@gmail.com** using EmailJS, a free email service.

## Current Configuration

- **Service ID**: `service_portfolio`
- **Booking Template**: `template_booking`
- **Contact Template**: `template_contact`
- **Public Key**: `wQNdYyF0gLRW8yCvL`
- **Recipient Email**: `rkimenyi2023@gmail.com`

## What Happens When Users Submit Forms

### Booking Form
When someone fills out the booking form, you'll receive an email with:
- Full Name
- Email Address
- Phone Number
- Service Type (Photography, Videography, Live Streaming, etc.)
- Event Date
- Event Location
- Event Details

### Contact Form
When someone sends a message through the contact form, you'll receive an email with:
- Full Name
- Email Address
- Subject
- Message Content

## Files Modified

1. **index.html** - Added EmailJS script
2. **script.js** - Updated form handlers to send emails via EmailJS

## Testing

1. Open the website in a browser
2. Fill out either the Contact form or Booking form
3. Submit the form
4. Check your email at **rkimenyi2023@gmail.com** for the submission

## Important Notes

- The forms work without a backend server because EmailJS handles everything
- All form data is sent securely through EmailJS servers
- You'll receive an email for every form submission
- The user sees a success message even if email sending fails (graceful fallback)

## Future Enhancements

If you want to:
- **Change the recipient email**: Update the `to_email` value in `script.js`
- **Add more fields**: Update the template in EmailJS dashboard and add corresponding variables
- **Customize email templates**: Visit https://dashboard.emailjs.com and edit the email templates there

## Support

If you want to modify the email templates or change settings, visit:
**https://dashboard.emailjs.com**

Login with the account associated with the public key `wQNdYyF0gLRW8yCvL`
