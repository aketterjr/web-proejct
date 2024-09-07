# web-project
<h2>Requirements</h2>

The first step in making this project is to identify the requirements of the software. The requirements I have established for myself are as follows:
There will be 3 different types of accounts: User, Author, and Staff

Users:
- Users will be able to browse a list of comic books
    - These stories can be sorted by title, author, and     user rating (1-5 stars)
- Users can comment on each chapter of a comic book as it comes out
- Users can rate stories on a 5-star scale
- Users can create posts about their favorite stories on message boards
    - Users can also comment on the posts of others
    - The components of a post will be author, subject, content, date/time
- Users can see their profile, including what comic books they follow, what users they are following, as well as the posts they have made on the message board
    - Users can also see the profiles of others
- Users can upload payment information for a monthly subscription which will enable special features
    - Viewing uploads earlier and getting access to the full catalogue of stories (older chapters of a story will be inaccessible wihtout a membership)

Staff:
- Staff members can moderate forums
    - Delete posts, delete user accounts (when the user requests to delete their account), temporarily ban users who violate terms of service
- Staff approves the creation of author accounts as well as other staff
- Staff accounts are not visible to users (they do not have a profile)

Author:
- Authors have all the same functions as users but with the added benefit of being able to post stories to the website
- Authors do not have the option to pay for a membership since it is free for them
- Author accounts have a special marker to show that they are an author

<h2>Architecture</h2>

The next step in the software development cycle is designing an architecture for the system based on these requirements. This will be accomplished with a UML diagram of the system as a whole.

![uml-diagram](/img/IMG_3264.JPG)