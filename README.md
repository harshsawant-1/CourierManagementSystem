# CourierManagementSystem
# Courier Management System (CMS)  ## Overview  The **Courier Management System (CMS)** is a web-based application built with PHP and MySQL designed to automate and streamline courier service operations. The system covers tasks such as booking couriers, tracking delivery statuses, and managing staff and branch information. 
# Courier Management System (CMS)

**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***-**-***

The Courier Management System (CMS) is a web-based application developed using PHP and MySQL. It is designed to handle the daily operations of a courier service, including booking couriers, tracking delivery statuses, managing staff, and maintaining branch information. This project simplifies the courier management process by computerizing tasks that would otherwise be done manually, making it more efficient and secure.

## Features

### Admin Module:
- **Dashboard**: View a summary of courier activities such as total shipments, pickups, in-transit packages, and deliveries.
- **Branches**: Manage branch details (add, update, delete).
- **Staffs**: Manage staff members (add, update, delete).
- **Courier**: Track and manage courier statuses and details filled by branch staff.
- **Complaints**: View and manage complaints raised by users and provide solutions.
- **Pages**: Update content for "About Us" and "Contact Us" pages.
- **Enquiries**: View inquiries submitted by users.
- **Reports**: Generate courier, delivery, and sales reports based on date filters.
- **Profile Management**: Update profile, change password, and recover password.

### Staff Module:
- **Dashboard**: Overview of courier activities such as pickups, in-transit shipments, and deliveries.
- **Add Courier**: Record parcel details.
- **Status**: View and update the status of courier packages.
- **Search Courier**: Search for courier details using the tracking number or reference number.
- **Profile Management**: Update profile, change password, and recover password.

### User Module:
- **View Status**: Track the delivery status of parcels.
- **Branches**: View the available branches of the courier company.
- **Complaints**: Raise and track complaints related to courier services.
- **Contact**: View company contact details and submit inquiries.

## Technologies Used
- **Frontend**: HTML, AJAX, jQuery, JavaScript
- **Backend**: PHP 5.6, PHP 7.x
- **Database**: MySQL 5.x
- **Web Browser Support**: Mozilla, Google Chrome, IE8, Opera
- **Server**: XAMPP / WAMP / LAMP

## Project Screenshots
- **Home Page**
- **Courier Home Page**
- **Raise Complaint Page**
- **Admin Login Page**
- **Admin Dashboard**
- **Courier Details Page**

## Installation Steps

1. **Download the Project**: Download the project from the repository as a zip file.
2. **Extract the File**: Extract the zip file and copy the `cms` folder.
3. **Move to Web Directory**: 
    - For XAMPP: paste the folder inside `xampp/htdocs`
    - For WAMP: paste inside `wamp/www`
    - For LAMP: paste inside `/var/www/html`
4. **Setup Database**:
    - Open [PHPMyAdmin](http://localhost/phpmyadmin)
    - Create a new database named `cmsdb`
    - Import the `cmsdb.sql` file located in the SQL folder of the project package
5. **Run the Application**:
    - Frontend: [http://localhost/cms](http://localhost/cms)
    - Admin Panel: [http://localhost/cms/admin](http://localhost/cms/admin)
    - Staff Panel: [http://localhost/cms/staff](http://localhost/cms/staff)

## Login Credentials

### Admin Panel
- **Username**: admin
- **Password**: Test@123

### Staff Panel
- **Username**: abc@gmail.com
- **Password**: Test@123
  Or register a new staff member via the admin panel.

### User Panel
For user tracking, use reference number: **809274137**

## Encryption:
The project uses MD5 encryption for password protection.

## Last Updated:
03-Dec-2023

---

For any issues or questions, feel free to raise them in the repository's Issues section.

