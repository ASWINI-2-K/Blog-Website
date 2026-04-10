# BLOG WEBSITE

## PROJECT OVERVIEW

This is a complete blog website built using Python Flask framework. The website allows users to perform all CRUD operations - Create, Read, Update, and Delete blog posts. The frontend is designed using Bootstrap 5 to ensure a clean and responsive user interface. All blog posts are stored in an SQLite database managed through SQLAlchemy ORM.

## PURPOSE

The purpose of this project is to create a fully functional blogging platform where users can write and publish their own articles. It provides an open platform for writing and sharing content with others. Users can interact with the content by submitting their own articles, editing them, or deleting them when needed.

## TECH STACK USED

| Category | Technology |
|----------|------------|
| Backend Framework | Python Flask |
| Database | SQLite |
| ORM | SQLAlchemy |
| Frontend | HTML5, CSS3 |
| CSS Framework | Bootstrap 5 |
| Icons | Font Awesome |
| Version Control | Git |

## COMPLETE FEATURES LIST

1. CREATE POST
   - Users can write new blog posts
   - Form with title and content fields
   - Both fields are mandatory
   - Posts are saved to database

2. READ POST
   - All posts are displayed on homepage
   - Posts appear in reverse chronological order
   - Each post shows title, content, and date
   - Preview of content shown on homepage

3. UPDATE POST
   - Users can edit existing posts
   - Pre-filled form with existing data
   - Changes are saved to database
   - Success message shown after update

4. DELETE POST
   - Users can delete unwanted posts
   - Confirmation dialog before deletion
   - Post is permanently removed from database
   - Success message shown after deletion

5. RESPONSIVE DESIGN
   - Works on desktop computers
   - Works on tablets
   - Works on mobile phones
   - Layout adjusts automatically

6. USER FEEDBACK
   - Flash messages for all actions
   - Success messages in green
   - Error messages in red
   - Messages disappear automatically

## DATABASE SCHEMA

Table Name: Post

| Column Name | Data Type | Constraints | Description |
|-------------|-----------|-------------|-------------|
| id | Integer | Primary Key, Auto-increment | Unique identifier for each post |
| title | String (100) | Not Null | Title of the blog post |
| content | Text | Not Null | Main content of the blog post |
| date_created | DateTime | Default = Current Time | Timestamp when post was created |

## FILE STRUCTURE
