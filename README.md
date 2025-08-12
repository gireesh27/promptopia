
# Promptopia

https://promptopia-gireeshs-projects-07740971.vercel.app/

Promptopia is an open-source AI prompting tool for the modern world to discover, create, and share creative prompts. This full-stack application allows users to leverage their creativity and share it with a community of like-minded individuals.

## About The Project

This project is a full-stack application built with Next.js that enables users to share and discover creative prompts for various AI platforms. Users can sign in using their Google accounts, create new prompts, edit or delete their existing prompts, and view prompts created by other users. The application is designed to be a hub for creative individuals to find inspiration and share their own unique ideas.

### Tech Stack

  * **Frontend:**
      * [Next.js](https://nextjs.org/)
      * [React](https://reactjs.org/)
      * [Tailwind CSS](https://tailwindcss.com/)
  * **Backend:**
      * [Next.js API Routes](https://nextjs.org/docs/api-routes/introduction)
  * **Database:**
      * [MongoDB](https://www.mongodb.com/)
      * [Mongoose](https://mongoosejs.com/)
  * **Authentication:**
      * [NextAuth.js](https://next-auth.js.org/) (with Google Provider)

## Features

  * **User Authentication**: Secure sign-in and sign-out functionality using Google accounts/route.js].
  * **Create Prompts**: Authenticated users can create new prompts by providing a prompt text and a relevant tag.
  * **Edit and Delete Prompts**: Users have full control over their own prompts and can edit or delete them at any time/route.js].
  * **Discover Prompts**: A dynamic feed allows users to view a collection of all prompts created by the community.
  * **Search Functionality**: Users can easily search for prompts by username, tag, or specific content within the prompt itself.
  * **User Profiles**: Each user has a dedicated profile page showcasing all the prompts they have created.
  * **View Other User's Profiles**: Users can visit the profiles of other creators to see all of their prompts/page.jsx].
  * **Copy to Clipboard**: A convenient "copy" button on each prompt card allows for easy copying of prompt text.

## Author

  * **Gireesh**

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

  * npm
    ```sh
    npm install npm@latest -g
    ```

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/gireesh27/promptopia.git
    ```
2.  Install NPM packages
    ```sh
    npm install
    ```
3.  Create a `.env.local` file in the root directory and add the following environment variables:
    ```env
    GOOGLE_CLIENT_ID=
    GOOGLE_CLIENT_SECRET=
    MONGODB_URI=
    NEXTAUTH_URL=http://localhost:3000
    NEXTAUTH_URL_INTERNAL=http://localhost:3000
    NEXTAUTH_SECRET=
    ```
4.  Start the development server
    ```sh
    npm run dev
    ```
