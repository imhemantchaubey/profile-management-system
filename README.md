[![License](https://img.shields.io/github/license/imhemantchaubey/profile-management-system)](https://opensource.org/licenses/gpl-license)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://opensource.org/licenses/gpl-license)

# <img src="https://cdn.pixabay.com/photo/2020/07/14/13/07/icon-5404125_1280.png" width="25"> Profile Management System

### 📌Home page:
<img src="https://user-images.githubusercontent.com/89316018/179353169-491481b5-b90a-4528-ade1-38758d0dcd7c.gif" height="200" width="auto">

### 📌Login page:
<img src="https://user-images.githubusercontent.com/89316018/179353190-8a74b9b7-7a46-40b3-8367-8b0c0e167ef7.gif" height="200" width="auto">

### 📌Register page:
<img src="https://user-images.githubusercontent.com/89316018/179353205-8bc145fd-b9a6-4c1d-abe4-c9dca37da856.gif" height="200" width="auto">

### 📌Update Profile page:
<img src="https://user-images.githubusercontent.com/89316018/179353220-02c62aec-d1df-478f-928d-4f0bcc975da5.gif" height="200" width="auto">

### 📌Database:
<img src="https://user-images.githubusercontent.com/89316018/179353233-6db96c5d-f9d4-49bc-b34d-70047be73b6b.gif" height="200" width="auto">

## 📌MYSQL Database:
```
CREATE TABLE users (
  id int(100) NOT NULL,
  name varchar(100) NOT NULL,
  email varchar(100) NOT NULL,
  password varchar(100) NOT NULL,
  dob date DEFAULT NULL,
  blood varchar(5) DEFAULT NULL,
  alergies varchar(100) DEFAULT NULL,
  weight int(11) DEFAULT NULL,
  image varchar(100) NOT NULL
);

ALTER TABLE users
  ADD PRIMARY KEY (id);

ALTER TABLE users
  MODIFY id int(100) NOT NULL AUTO_INCREMENT;
COMMIT;
```

- Enjoy coding...
- Thank you...