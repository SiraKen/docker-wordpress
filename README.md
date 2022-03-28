# WordPress for Docker Compose

## Set up

1. Execute `./runner up`.
2. Access to `http://localhost:8080`.
3. Initial set up WordPress.
4. Remove unnecessary themes.
5. Copy the theme folder you want to customize into `wp-content/themes`.
6. Enable the theme on WordPress.

## MySQL

- MySQL is available on `localhost:3307`.
- Username: wp_user
- Password: wp_user

## Git

- Remove the statement that ignores files under `wp-content` from `.gitignore` before you commit.
