
Additionaly  do some necessary changes in the Backend<br>

1. Fixes Some bug issues After Testing The API<br>;
2. Implement some Error handling cases<br>
3. implement Validation on Necessary places<br>
4. Added Download Functionality For the User to Download the Converted File


# File Converter Frontend<br>

This is the frontend of the File Converter utility tool, built using **Next.js** and styled with **ShadCN UI** components. It provides an intuitive interface for converting files between formats by interacting with a Flask-based backend.<br>

## Features<br>

- **Modern UI**: Designed with ShadCN components for a clean and professional look<br>
- **File Conversion**:<br>
  - PDF to Word<br>
  - Images to PDF<br>
- **Real-Time Feedback**:<br>
  - File upload progress and error messages.<br>
- **Scalable Design**:<br>
  - Built with modularity for adding more tools and features in the future.<br>

### Prerequisites<br>

- Node.js (>= 16.0.0)<br>
- npm or yarn package manager<br>

   
##Pages and Features
1.Home Page (/)<br>
Introduces the tool and provides navigation to the conversion features.<br>

2.PDF to Word (/pdf_to_word)<br>
Allows users to upload a PDF file for conversion to Word.<br>
Displays real-time conversion status and provides a download link for the converted file.<br>

3.Image to PDF (/image_to_pdf)<br>
Enables users to upload one or more image files to combine into a single PDF.<br>
Offers feedback on file upload progress and success/failure messages.<br>

##Key Components<br>
1.Navbar<br>
Simple navigation menu for accessing features.<br>
Found in components/Navbar.js.<br>

2.FileUpload<br>
Reusable form component for uploading files and triggering conversions.<br>
Found in components/FileUpload.js.<br>

3.ProgressBar<br>
Displays the progress of file uploads in real-time.<br>
Found in components/ProgressBar.js.<br>

4.Styling<br>
Global Styles: Defined in styles/globals.css.<br>






