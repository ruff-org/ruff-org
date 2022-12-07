# Blazed One
The Blazed One application will be a social networking site and activity hub for Blazed Labs and clients.

## Scope
The project will include a frontend application (available at [blz.one](https://blz.one/)) as well as a backend.

## Features
- User Accounts and Profiles, Pages and Groups
- Text and Multimedia Posts
- Messaging
- Activity
- Privacy
- Following
- Reactions to posts and Commenting

## Implementation
Under the hood, Blazed One will use [Laravel Jetstream](https://jetstream.laravel.com/). This boilerplate provides authentication, basic profile, and even session management. The Socialite package will be used to integrate with Google, Facebook, and Twitter.

The application will store its data in a MySQL database. [Laravel Echo](https://laravel.com/docs/broadcasting#client-side-installation) will be installed to a server to push real-time updates using websockets. [Laravel Notifications](https://laravel.com/docs/9.x/notifications) will be used for status updates. Finally, [Voyager](https://voyager.devdojo.com/) will be used to add an admin panel to the application.

The application will be deployed to [Render](https://render.com/).

## Timeline
- Deadline: **March 2023**