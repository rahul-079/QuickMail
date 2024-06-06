
---

# QuickMail README

QuickMail is a web application designed to simplify the process of sending bulk emails to multiple recipients. Built on the EmailJS platform, QuickMail provides a user-friendly interface for composing, dispatching emails efficiently, and sorting and validating email addresses from CSV files to ensure that only valid email addresses are used.
## Getting Started

To get started with QuickMail, follow these steps:

1. **Create an EmailJS Account**:
   - QuickMail utilizes EmailJS services for email functionalities. You'll need a valid EmailJS account to integrate email sending capabilities into the application.

2. **Retrieve User ID**:
   - After creating an EmailJS account, navigate to your account settings, specifically the "General" section, to find your User ID. This ID is essential for authentication purposes.

3. **Create Service and Obtain Service ID**:
   - Within EmailJS, you need to create a service first. Go to the "Email Services" section and click on "Add New Service". Choose your preferred email provider from the list and connect your email account to the service. Upon successful connection, you will receive a Service ID.

4. **Create Email Template and Obtain Template ID**:
   - Create an email template within EmailJS. Ensure that the template contains all necessary placeholders and content for your emails. Make any customizations required. Once the template is created, you will receive a Template ID.
   - The Subject ,To Email and From Name should have the same values as shown in the below image.
   - The content box must contain {{message_html}} and you can add additional text or content if you want to.
    
    ![template](https://github.com/rahul-079/QuickMail/assets/121021984/8853f494-9ecb-44f9-ad4a-6f7fc95b4b0f)

5. **Ensure Correctness of IDs**:
   - Double-check that the User ID, Service ID, and Template ID used in QuickMail match the IDs obtained from your EmailJS account. Incorrect IDs may lead to email sending failures.

6. **Usage**:

   To use the QuickMail project, follow these steps:
   - **Upload a CSV File**:
     Start by uploading a CSV file containing email addresses. The system will automatically validate and sort the email addresses, separating the valid and invalid ones.

   - **Enter Email Details**:
    After uploading the CSV file, enter the email subject, body, and any other necessary details.

   - **Send Emails**:
     Click on the send button to dispatch the emails to the recipients.
     
## Dependencies

The Mass Mail Dispatcher project uses the following dependencies:

- **EmailJS API** ([emailjs.com](https://www.emailjs.com)):
  - EmailJS is used to handle email sending functionality within the application.

## TroubleShooting

If you encounter any issues when running the Mass Mail Dispatcher project, try the following solutions:

- Ensure that you have uploaded a CSV file containing valid email addresses.
- Please ensure that all required fields have been entered correctly

## Contributing

Contributions to QuickMail are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request on the GitHub repository.

## Contact Information

For any inquiries or support regarding QuickMail, you can reach out to the project creator:

- **Name**: Rahul
- **Email**: rahul.chandu321@gmail.com
- **LinkedIn**: [Rahul's LinkedIn Profile](https://www.linkedin.com/in/rahul-pamu-b7a3b0248/)
- **GitHub**: [Rahul's GitHub Profile](https://github.com/rahul-079)

---
______________________THANK YOU!______________________
