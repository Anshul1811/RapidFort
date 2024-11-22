
# Doc2PDF

## Overview

**Doc2PDF** is a full-stack application designed to convert Microsoft Word documents (`.doc` and `.docx`) into PDF format. The app is built using React.js for the frontend and Node.js with Express for the backend. It features a responsive design and supports both dark and light themes. The application uses Tailwind CSS for styling and includes various tools and libraries for development.

## Technologies Used

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express
- **Styling**: Tailwind CSS
- **Development Tools**: Vite, Nodemon
- **Libraries**:
  - `multer` (for handling file uploads)
  - `docx-pdf` (for converting Word documents to PDF)

## Installation

### Frontend

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Doc2PDF.git
   cd Doc2PDF
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Development Server**:
   ```bash
   npm start
   ```

   Open your browser and navigate to `http://localhost:3000` to view the application.

### Backend

1. **Navigate to the Backend Directory** (if it's a separate directory):
   ```bash
   cd server
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the Server**:
   ```bash
   nodemon server.js
   ```

   Ensure the backend server is running and accessible.

## Usage

1. **Open the Application**: Go to `http://localhost:3000` in your browser.
2. **Upload a File**: Click on the "Choose File" button to select a `.doc` or `.docx` file from your computer.
3. **Convert the File**: Click on the "Convert File" button to start the conversion process.
4. **Download the PDF**: Once the conversion is complete, you will be provided with a download link for the converted PDF file.

## Configuration

- **API Endpoint**: The frontend is configured to communicate with the backend API endpoint at `http://localhost:3000/convertFile` (adjust if necessary).

## Testing

Use Postman to test the API endpoints:
- **Upload File**: `POST /convertFile` with `multipart/form-data` containing the file.


