## StudyNotion Edtech Project

Here is the Live Link-> 

# Architecture Diagram 

Here is a high-level diagram that illustrates the architecture of the StudyNotion ed-tech platform:
![image](https://github.com/user-attachments/assets/6ef6a023-ebe8-48f8-a9f6-80222366ab1e)
---

The front end of StudyNotion has all the necessary pages that an ed-tech platform should have. Some of these pages are:

# For Students:

Homepage 🏠: A brief introduction to the platform with links to the course list and user details and random background.
Course List 📚: A list of all the courses available on the platform, along with their descriptions and ratings.
Wishlist 💡: Displays all the courses that a student has added to their wishlist.
Cart Checkout 🛒 : Allows the user to complete course purchases.
Course Content 🎓: Presents the course content for a particular course, including videos and related material.
User Details 👤: Provides details about the student's account, including their name, email, and other relevant information.
User Edit Details ✏️: Allows students to edit their account details.

# For Instructors:

- Dashboard 📊: Offers an overview of the instructor's courses, along with ratings and feedback for each course.
- Insights 📈: Provides detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
- Course Management Pages 🛠️: Enables instructors to create, update, and delete courses, as well as manage course content and pricing.
- View and Edit Profile Details 👀: Allows instructors to view and edit their account details.
  
# Back-end ⚙️

The back-end of the platform is built using NodeJS and ExpressJS, providing APIs for the front-end to consume. These APIs include functionalities such as user authentication, course creation, and course consumption. The back-end also handles the logic for processing and storing the course content and user data.

Back-end Features
- User Authentication and Authorization 🔐: Students and instructors can sign up and log in to the platform using their email addresses and passwords. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
- Course Management 🛠️: Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
- Payment Integration 💳: Students will purchase and enroll in courses by completing the checkout flow, followed by Razorpay integration for payment handling.
- Cloud-based Media Management ☁️ : StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
