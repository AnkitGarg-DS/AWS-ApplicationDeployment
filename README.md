# AWS-ApplicationDeployment
## 1. Backend Configuration:

  ### Clone the repository and navigate to the backend directory.
  <img width="940" height="289" alt="image" src="https://github.com/user-attachments/assets/23e87468-c104-4f3f-8e3e-0af070a2cc8a" />

  ### The backend runs on port 3000. Set up a reverse proxy using nginx to ensure smooth deployment on EC2.
  <img width="940" height="405" alt="image" src="https://github.com/user-attachments/assets/a44fbf22-6234-4b85-9304-5142b8fd792a" />

  ###  Update the .env file to incorporate database connection details and port information
  <img width="940" height="125" alt="image" src="https://github.com/user-attachments/assets/41386df6-a641-4044-872c-31e33f3ba042" />

## 2. Frontend and Backend Connection:

  ### Navigate to the `urls.js` in the frontend directory.
  ### Update the file to ensure the front end communicates effectively with the backend.

  <img width="940" height="139" alt="image" src="https://github.com/user-attachments/assets/bacad054-1f76-4b77-8060-c89cf4796435" />
  <img width="939" height="550" alt="image" src="https://github.com/user-attachments/assets/8adac14d-7db6-4a81-9f9b-28d6c364bbf3" />
  <img width="769" height="531" alt="image" src="https://github.com/user-attachments/assets/af37824c-6d65-4643-bf41-3c5318bd72e9" />

## 3. Scaling the Application:

  ### Create multiple instances of both the frontend and backend servers.
  <img width="940" height="205" alt="image" src="https://github.com/user-attachments/assets/3210f417-8505-44a2-b707-0b237295ba31" />

  ### Add these instances to a load balancer to ensure efficient distribution of incoming traffic
  <img width="940" height="177" alt="image" src="https://github.com/user-attachments/assets/8ef4336e-74da-44bb-bc75-7a3a8b8b8172" />
  <img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/5452b53e-d6ee-4459-bba0-23a63f9a7b57" />
  <img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/b84cd29a-fe8f-4247-8060-580b9ac54944" />
  <img width="940" height="431" alt="image" src="https://github.com/user-attachments/assets/dc0a429f-956e-4d4b-9f44-a26d4e701482" />

  <img width="940" height="848" alt="image" src="https://github.com/user-attachments/assets/4b908b9d-0ca0-40f6-858c-aef6344b9afd" />
  <img width="940" height="133" alt="image" src="https://github.com/user-attachments/assets/d1d00e86-3ee2-4b8a-8ca7-46d5980b89d9" />
  <img width="940" height="117" alt="image" src="https://github.com/user-attachments/assets/aacf87f6-dc6d-403d-98d2-c8aea36f25a8" />

## 4. Domain Setup with Cloudflare

  ### Prepare comprehensive documentation detailing each step of the deployment process. Include relevant screenshots to make the process clear and reproducible.
  ### Design a deployment architecture diagram using [draw.io](https://www.draw.io/) to visualize the flow and connections.

  <img width="1814" height="421" alt="image" src="https://github.com/user-attachments/assets/c598ad90-ce8d-4246-b2bf-3bb1f96e5a05" />
  <img width="744" height="684" alt="image" src="https://github.com/user-attachments/assets/29c7b9ce-b2f2-4109-8dc3-2265b036c636" />
  <img width="368" height="126" alt="image" src="https://github.com/user-attachments/assets/427d4f1f-4fa6-4c85-995a-7e4eb49341ba" />
  <img width="402" height="113" alt="image" src="https://github.com/user-attachments/assets/52dd3787-f421-4e29-abba-c0172cf6ce8a" />



  











