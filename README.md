## Time-Capsule

- App Link (deploy on main branch):

https://time-capsule.onrender.com

### Created By

- Youfu Yan
- Isabel Dahl
- Marcellinus, Steven Sugiarto
- Ying Lu

## Key Features

- Applied a decorator to restrict some actions (such as commenting or liking) for users who are not logged in.
- Implemented full text search and fuzzy search to allow users to find photos based on their captions or descriptions.
- Realized Responsive design that makes web pages render well on different devices and screen sizes and adaptable to mobile devices.
- Implemented comment and like system to enable real-time communication and feedback among users without reloading the page.

## Testing Notes

1. Click the 'exploring' button on the landing page to see the gallery
2. Without logging in, click any post to see the comments page
3. Without logging in, click the like button or comment button to redirect to the landing page
4. Without logging in, click the search button to search for posts by keywords or hashtags
5. Without logging in, click the 'add new post' button to redirect to the landing page
6. Click the 'login' button on the landing page to login
7. After logging, click the 'add new post' button to add a new post
8. After logging, click the 'search' button to search for posts by keywords or hashtags
9. After logging, click the 'like' button to like a post
10. After logging, click the 'comment' button to comment on a post
11. After logging, click the 'profile' button to see the profile page
12. On the profile page, click the 'edit profile' button to edit the profile and click the 'save' button to save the changes
13. On the edit profile page, click the 'delete' button to delete a post
14. Click the 'logout' button to logout and redirect to the landing page

## Screenshots of Site

### Gallery

![Gallery](./Demo/gallery.png 'Gallery')

### Search

![Search](./Demo/search.png 'Search')

### Add new post

![Add new post](./Demo/addpost.png 'Add new post')

### Comments

![Comments](./Demo/comment.png 'Comments')

### Profile

![Profile](./Demo/profile.png 'Profile')

## External Dependencies

- Web Hosting: [Render](https://render.com/)
- Database: [PostgreSQL on Render](https://render.com/docs/postgres)
- Photo Storage: [Imagekit](https://imagekit.io/)
- Authentication: [Auth0](https://auth0.com/)

# Legacy

## Mock-up

### Preview

![](./Mockups/1.png 'Adding new post')
![](./Mockups/2.png 'Searching')
![](./Mockups/3.png 'Gallery')
![](./Mockups/4.png 'Comments')
