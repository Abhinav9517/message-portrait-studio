 # Message Portrait Studio

  Turn any photo into a portrait built from your words. Message Portrait Studio
  transforms an uploaded image into a high-resolution text portrait using a custom
  message, then lets you download the result as a PNG.

  ## Live Demo

  [View the live demo](https://your-username.github.io/message-portrait-studio/)

  ## Screenshot / GIF

  ![Message Portrait Studio preview](./assets/screenshot.png)

  If you prefer, you can also add a short GIF here to show the interaction in
  motion.

  ## Features

  - Upload any portrait photo
  - Type a custom message to generate the artwork
  - Adjust density, contrast, brightness, gamma, and warmth
  - Preview the original image and the rendered output side by side
  - Download the final portrait as a PNG
  - Built to work fully in the browser

  ## How It Works

  The app uses the Canvas API to read the uploaded image, down-sample it, and
  convert the image data into a text-based portrait. Lighter and darker regions are
  mapped to character placement and ink intensity, while the chosen message is
  repeated across the canvas to form the final artwork. The result is rendered at
  high resolution so it can be downloaded and shared.

  ## How To Run Locally

  1. Clone the repository:
     ```bash
     git clone https://github.com/your-username/message-portrait-studio.git

  2. Open the project folder:

     cd message-portrait-studio

  3. Open index.html in your browser.

     You can also run a local server if you prefer:

     python -m http.server 8000

     Then visit:

     http://localhost:8000

  ## Screenshot
    <img width="463" height="777" alt="img5" src="https://github.com/user-attachments/assets/ea30eb41-b388-49aa-9c4b-84fc50ebc8f8" />
<img width="242" height="700" alt="img4" src="https://github.com/user-attachments/assets/9c87d3f6-a911-4e1f-8f2d-5dd00cd83f4e" />
<img width="395" height="668" alt="img3" src="https://github.com/user-attachments/assets/f84cdc4f-3512-4e96-9702-c4bef5c61d6b" />
<img width="378" height="285" alt="img2" src="https://github.com/user-attachments/assets/0b3aee5f-2201-469c-940e-b9a2d2bf9c90" />
<img width="385" height="377" alt="img1" src="https://github.com/user-attachments/assets/9e9e2b7f-20aa-40e1-9b29-0ae984e4c889" />

  ## Tech Stack

  - HTML
  - CSS
  - JavaScript
  - Canvas API

  ## License

  This project is licensed under the MIT License. See the LICENSE (LICENSE) file for
  details.
