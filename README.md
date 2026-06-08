# Transactions API Deployment

## Reflection & Project Details

### What were the new things you learned in this activity?
I learned how to properly containerize a Node.js/Express application using Docker and `docker-compose`, specifically how to manage networking between a Node container and a MongoDB container. I learned about login heroku

### What is the purpose of the `seed.js` program?
This ensures that when the API starts up in a new environment (like inside a fresh Docker container or immediately after deployment), there is already data available to query and test against, saving the time of manually inserting records.

### What was the most difficult thing to do in this activity?
The most difficult part was troubleshooting the connection and deployment transitions between the local environment, Docker, and Heroku.

### How would you say you were prudent in this assignment?
I was prudent by actively utilizing logs (`heroku logs --tail`) to pinpoint the exact source of crashes rather than guessing what went wrong.

### How would you say you need to be prudent when developing this kind of web applications?
When developing full-stack web applications, it is crucial to be prudent with security and environment parity. This means strictly managing secrets 

---

## URL
https://deploy1-4cc8d5963368.herokuapp.com

---

## Postman Testing Screenshots

<img width="1512" height="982" alt="Screenshot 2026-06-08 at 9 31 48 AM" src="https://github.com/user-attachments/assets/f36e0fc6-5e99-43ce-ad87-4e8b0d01a55b" />
<img width="1512" height="982" alt="Screenshot 2026-06-08 at 9 27 16 AM" src="https://github.com/user-attachments/assets/be4d9c81-d2b5-40aa-9eb5-9a63d58d92ae" />
<img width="1512" height="982" alt="Screenshot 2026-06-08 at 9 36 27 AM" src="https://github.com/user-attachments/assets/9146502b-cf2e-4332-a5d0-4c5054b71b2e" />
<img width="1512" height="982" alt="Screenshot 2026-06-08 at 9 43 17 AM" src="https://github.com/user-attachments/assets/3f77e5cb-01c5-4634-8455-fde94577d08e" />

