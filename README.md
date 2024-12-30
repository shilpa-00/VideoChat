# Video Chat Application

This is a simple Video Chat application built using the WebRTC.

## Installation

Follow these steps to get the project up and running on your local machine.

1. **Clone the Repository:**
   
First, clone this repository to your local machine:
```
git clone <repository-url>
cd <project-directory>
```

2. **Install Dependencies:**
   
Navigate to the project directory in your terminal and install the necessary dependencies.
```
npm install
```

3. **Install PeerJS**

The Port number for PeerJS is configured as 3001 for this application. Open a seperate terminal and run the following commands.

Run the following command to install peerJS into your machine(globally).
```
npm i -g peer
```

Run the following command to start the server
```
peerjs --port portno.
```

(or)

Run the following command to install peerJS into your machine(globally).
```
npm i peer
```

Run the following command to start the server
```
npx peerjs --port portno
```

4. **Start the Application:**
   
After that start the application by running the following command:\
```
npm start
```

5. **Open the Application:**
   
Once the application starts running, open your browser and go to http://localhost:3000 to start a video chat. Copy the same URL and open in another browser to connect to the same ROOM ID.
