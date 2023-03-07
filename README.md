

<h2>Wordpress setup</h2>

1. `directory/xamp/htdocs` create new folder named `wordpress` <br>
![image](https://user-images.githubusercontent.com/82623435/223330222-c8c84ea0-290b-4a24-b1dd-2c436eff3129.png)

2. move provided files inside created folder <br>
![image](https://user-images.githubusercontent.com/82623435/223330362-26e7aa0a-896b-477c-938e-cde85d5cbbfe.png)

3. go to http://localhost/phpmyadmin/index.php?route=/server/privileges&viewing_mode=server and create user with database (checkbox) `username`: 'ccadmin', `psw`: `ccadmin`   <br>
![image](https://user-images.githubusercontent.com/82623435/223334550-665b14d4-3d01-48be-9a5d-a8095f992ee1.png)

4. go to http://localhost/wordpress/installer.php Press `Validate`<br>
![image](https://user-images.githubusercontent.com/82623435/223334636-91172a8d-1824-45b6-9c49-010704627376.png)

5. Check checkbox and press `Next` <br>
![image](https://user-images.githubusercontent.com/82623435/223334891-747d8c17-c852-4fd7-8948-f47830e166a4.png)

6. Press `Admin login` <br>
![image](https://user-images.githubusercontent.com/82623435/223335089-99f2b86c-f1b4-45ff-ba69-426c142d8289.png)

7. Login with old credentials in wordpress login screen   <br>

<h2>Front end (Reactjs) setup</h2>

1. Go to `\xampp\htdocs\wordpress\wp-content\plugins\frontend\src` folder and run `npm i`
2. After installation finishes run `npm run`
3. new tab in web browser should pop up. It takes `Posts` endpoint (`Posts` used as `Products` in this case) and renders data in web browser.
