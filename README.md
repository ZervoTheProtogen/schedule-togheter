# ScheduleTogether

Web application to share schedules with your friends

## Running the project

1. Install MariaDB / MySQL and run as root

2. Create user from credentials found in [config.json](./server/config.json)

```
CREATE USER 'scheduleuser'@'localhost' IDENTIFIED BY 'somepass';
```

3. Clone it
```
git clone https://github.com/ZervoTheProtogen/schedule-together.git
```

4. CD Into server directory
```
cd ./schedule-together/server
```

5. Install components and run server
```
npm install
```

```
npm run dev
```

6. In a new terminal (or after sending server to background), cd to frontend
```
cd ../frontend
```

7. Install components and run frontend
```
npm install
```

```
npm run dev
```

8. Test it in your browser

Go to [http://localhost:5173](http://localhost:5173/)

## TODO

- [x] Add functionality to userlist searchbar
- [ ] Hide admin option in navbar/sidebar for users
- [ ] Restrict access to admin pages
- [ ] Restrict access to API admin actions
- [ ] Add account and notifications menu
- [ ] Style the admin dashboard
- [ ] Add confirmation dialouge for user deletion
- [ ] Add view for the schedule
- [x] Add basic frontend roles
- [x] Add basic backend roles