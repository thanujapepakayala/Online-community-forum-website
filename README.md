# Online-community-forum-website
# Community Forum Website(Apple Support Communities)

## Overview

The **Community Forum Website** allows users to register, create posts, navigate through categories, and engage with others through comments. All data related to users, posts, and comments is securely stored in a **PHP MySQL database**.

## Table of Contents

1. User Registration Module
2. Post Creation Module
3. Category Navigation Module
4. Comment System Module
5. Database
6. Prerequisites

---

## User Registration Module

### Purpose:
The User Registration Module enables users to securely register and log into the platform. It ensures that only verified users can create posts and participate in discussions.

### Functionality:
- **Input:**
  - **Name**: User's full name.
  - **Email**: A valid email address used to create the account.
  - **Password**: A secure password to protect the account.

### Key Features:
- **Secure Password Storage**: Passwords are encrypted and stored securely.
- **Email Verification**: Upon registration, users receive an email with a verification link to activate their account.
- **Input Validation**: Ensures that the email is in a correct format and the password meets security requirements.
![Image Description](https://drive.google.com/uc?export=view&id=1lITjjC-JmACinFIoc_JnU4jgJXHRKE4H)
---
![Example Image](https://drive.google.com/uc?export=view&id=1tPLj0rWFpxxTj8pGwp2goeY2fmvPXG2L)


---

## Post Creation Module

### Purpose:
The Post Creation Module allows users to create posts under different categories, such as iPhone, iPad, iCloud, Apple Watch, Mac, macOS, and iOS, and share their thoughts or queries with the community.

### Functionality:
- **Input:**
  - **Title**: The title of the post.
  - **Post Content**: The main body or text of the post.
  - **Category**: A predefined category selected by the user for the post.

### Key Features:
- **Rich Text Editor**: Users can format the content of their posts using basic text formatting tools.
- **Post Editing and Deletion**: After a post is created, users can edit or delete it at any time.
- **Category Selection**: Posts can be categorized for easier organization and browsing.
  ![Alt Text](https://drive.google.com/uc?export=view&id=1fdfkRT3ssSQytE4RGUZVMOfHdkEzg6qD)
 ![Alt Text](https://drive.google.com/uc?export=view&id=1wCi1t8fABnyMfNqHFPPYcl1JFtTPCoYU)



---

## Category Navigation Module

### Purpose:
The Category Navigation Module organizes posts into specific categories, making it easier for users to browse and find content that interests them.

### Functionality:
- **Input:**
  - User-selected category to filter posts.

### Key Features:
- **Category Selection Menu**: A menu to choose categories and browse posts under them.
- **Filtering Options**: Additional filtering to sort posts by date, popularity, or other criteria.

### Categories:
- **Apple Watch**
- **iCloud**
- **iOS**
- **iPad**
- **iPhone**
- **Mac**
- **macOS**
  ![Alt Text](https://drive.google.com/uc?export=view&id=1TfVAkvyVs0q-lVJH6x0l1am_PBrLtg13)
  ![Alt Text](https://drive.google.com/uc?export=view&id=1qd_5WOBEml8NNW3hK7NkkAjsXr0J-6ks)



---

## Comment System Module

### Purpose:
The Comment System Module allows users to comment on posts, participate in discussions, and provide feedback.

### Functionality:
- **Input:**
  - **Comment Text**: The content of the comment.
  - **Optional Upvote/Downvote**: Users can vote on comments to express approval or disagreement.

### Key Features:
- **Comment Editing**: Users can edit their comments after posting them.
- **Upvoting and Downvoting**: Allows users to upvote or downvote comments to indicate their approval or disagreement.
- **Nested Comments**: Support for replying to comments, creating threads within the discussion.
  ![Alt Text](https://drive.google.com/uc?export=view&id=1QYpOgOFjIMvmjRoorKnAp-iMoAsV9BLm)


---

## Database

The PHP MySQL database stores all the relevant data for the Community Forum Website.

### Tables:

- **category_list**: Stores the categories under which posts are organized.
- **comment_list**: Stores user comments on posts.
- **post_list**: Stores post details including title, content, category, and the user who created the post.
- **system_info**: Stores details about the system or forum settings (e.g., system configurations, admin settings).
- **users**: Stores user data like name, email, password, and verification status.
  ![Alt Text](https://drive.google.com/uc?export=view&id=1IzFbFqPqFL_cDYZ6cCUGwyIjgzmU0BF6)
  ![Alt Text](https://drive.google.com/uc?export=view&id=1VqoRwVM9PJD3TQOOoNwSUYiUpj36YLkX)
  ![Alt Text](https://drive.google.com/uc?export=view&id=1lBSbK68wh3FOwNS1zDFoNDWE276wo0M7)

  





## Prerequisites

To run the project, you will need to download and install PHP along with the XAMPP server on your local machine. XAMPP provides the necessary environment for running PHP and SQL databases locally. After installation, ensure you configure the server and database correctly to run the project smoothly.


