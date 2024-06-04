```markdown
# Campground Booking Website

This is a campground booking website built using Node.js, MongoDB, EJS, and CSS.

## Features

- Users can view a list of campgrounds available for booking.
- Users can view details of each campground, including images, description, and amenities.
- Admin users can manage campgrounds, including adding, editing, and deleting them.
- Authentication system for users and admins.

## Technologies Used

- **Node.js**: JavaScript runtime for server-side development.
- **MongoDB**: NoSQL database used for storing campground and user data.
- **EJS**: Embedded JavaScript templating language for rendering dynamic content in HTML pages.
- **CSS**: Styling language for designing the user interface.
- **Express.js**: Web application framework for Node.js used for routing and middleware.
- **Passport.js**: Authentication middleware for Node.js used for user authentication.
- **Heroku**: Cloud platform used for hosting the application.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sb412/myproject.git
   cd your-repo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following environment variables:
     ```
     PORT=3000
     MONGODB_URI=your_mongodb_uri
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     SECRET=your_secret_key

     ```

4. Run the application:
   ```bash
   npm start
   ```

## Deployment

This application is deployed and hosted on Heroku. You can access it [here](https://safe-badlands-71078.herokuapp.com/).