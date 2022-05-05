# CSSE6400 Seq Cloud Formation Stack Instructions

1. In AWS, go to **CloudFormation** Service, go to **Stacks**, then **Create Stack**.

2. In **Create stack**
    a. Prepare template — "Template is ready"
    b. Sepcify template — "Upload a template file"
    c. Upload the seqcfn.yaml in this repository
    d. Click **Next**

![image](https://user-images.githubusercontent.com/7476736/166860269-1b22efaf-a324-4892-ac68-d4a438a087ff.png)

3. **Specify Stack Details**
    a. Name your stack whatever you want, we'll call it "Seq"
    b. Leave all the other defaults the same
    c. Click **Next**

![image](https://user-images.githubusercontent.com/7476736/166860395-302977e1-d350-4edb-9a86-8dc3689a1246.png)

4. **Configure stack options**
    a. Leave all the defaults
    b. Click **Next**
  
![image](https://user-images.githubusercontent.com/7476736/166860485-95e62b8f-2f77-43c6-b542-9b8a91fdbb88.png)

5. The stack creation will begin, you can monitor the progress in the last screen

![image](https://user-images.githubusercontent.com/7476736/166860564-ac25fb46-ad20-456e-b575-8d6e0120a0fd.png)

6. How to find out the Public IP address of the Seq instance (you can set up your own LB if you like).

![image](https://user-images.githubusercontent.com/7476736/166860644-f11c30d4-141b-4760-a295-bedd37f69fb3.png)

7. Go to the IP address above (no need to add port 5341, it's mapped to port 80), and log in using the default password, below.

```
Username: admin
Password: password
```

**Make sure you change the password as soon as you log in**
