# Magento2 Email to admin after registeration

Add email template from admin and add below code.

   <!-- Begin Content -->
<p>New customer created on website.</p>
<p><strong>Name:</strong> {{var data.name}}</p>
<p><strong>Email:</strong> {{var data.email}}</p>
<!-- End Content -->
