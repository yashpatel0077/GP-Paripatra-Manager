GP Paripatra Manager

GP Paripatra Manager is a WordPress plugin for managing and displaying Paripatra records in a clean table format. It allows admins to add Paripatra details, upload PDF files, and show records on the frontend with filters, pagination, download, and read links. 

## Features

- Custom Post Type for Paripatra entries
- Admin metabox for:
  - Paripatra Type
  - Date
  - Title
  - Subject
  - PDF Upload 
- WordPress media uploader support for PDF selection. 
- Frontend shortcode to display Paripatra records in a styled table. 
- Filter records by:
  - Date
  - Title
  - Subject
  - Type 
- Pagination support. 
- Duplicate record filtering based on Type + Date + Title + Subject. 
- Download and Read buttons for attached PDF files. 
- Responsive table layout for mobile devices. 
- Admin column for displaying Paripatra date in the post list. 

## Installation

1. Download or clone this repository.
2. Upload the plugin folder to your WordPress `/wp-content/plugins/` directory.
3. Go to **WordPress Admin > Plugins**.
4. Activate **GP Paripatra Manager**. 

## Usage

### Add New Paripatra

1. In WordPress Admin, open the **Paripatra** menu. 
2. Click **Add New**.
3. Enter the post title.
4. Fill in:
   - Paripatra Type
   - Date
   - Title
   - Subject
5. Upload or select a PDF file.
6. Publish the post. 

### Display on Frontend

Use this shortcode on any page or post:

```shortcode
[paripatra_table]
