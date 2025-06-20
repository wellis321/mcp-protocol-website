# Formspree Setup Guide

## Step 1: Create Formspree Account
1. Go to [formspree.io](https://formspree.io)
2. Click "Get started" and create a free account
3. Verify your email address

## Step 2: Create Your Form
1. In your Formspree dashboard, click "New Form"
2. Choose "HTML" as your form type
3. Give your form a name like "MCP Protocol Contact Form"
4. Copy the form endpoint URL (it will look like: `https://formspree.io/f/xpznvwqr`)

## Step 3: Update Your Website
1. Open `index.html`
2. Find this line: `<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">`
3. Replace `YOUR_FORM_ID` with your actual form ID from step 2

## Step 4: Configure Form Settings (Optional)
In your Formspree dashboard, you can:
- Set up email notifications
- Add spam protection
- Customize auto-response messages
- Set up integrations (like sending to Google Sheets)

## Step 5: Test Your Form
1. Fill out the form on your website
2. Submit it
3. Check your email for the form submission
4. Verify it appears in your Formspree dashboard

## Form Fields Explanation
Your form captures:
- **Name** (required)
- **Email** (required) 
- **Organisation** (optional)
- **Sector** (dropdown with options)
- **Message** (required) - asking how MCP can help

## Free Plan Limits
- 50 submissions per month
- Basic spam protection
- Email notifications

## Upgrade Benefits
- More submissions
- Advanced spam protection
- Integrations with tools like Slack, Google Sheets
- Custom thank you pages

## Need Help?
- Formspree documentation: https://help.formspree.io/
- Contact support through your dashboard 