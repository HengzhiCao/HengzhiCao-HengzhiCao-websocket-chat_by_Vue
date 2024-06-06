
# WebSocket Chat Application

This is a simple WebSocket chat application built with Vue.js and Bootstrap Vue.

## Features

- Real-time chat using WebSocket
- User identification with username
- Beautiful UI using Bootstrap Vue
- Fixed size chat window with scrollable message list
- Colorful background for chat components

## Project Structure

```
websocket-chat/
├── websocket-chat-client/
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   └── ChatComponent.vue
│   │   ├── plugins/
│   │   │   └── bootstrap-vue.js
│   │   ├── App.vue
│   │   ├── main.js
│   ├── package.json
│   ├── vue.config.js
│   ├── README.md
├── server.js
├── package.json
```

## Setup and Installation

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/websocket-chat.git
cd websocket-chat
```

2. Install server dependencies:

```bash
npm install
```

3. Install client dependencies:

```bash
cd websocket-chat-client
npm install
```

### Running the Application

1. Start the WebSocket server:

```bash
node server.js
```

2. Start the Vue.js client application:

```bash
cd websocket-chat-client
npm run serve
```

3. Open your browser and navigate to `http://localhost:8080`.

## Usage

1. Enter your username when prompted.
2. Type your message in the input field and press Enter or click the "Send" button to send the message.
3. Your message will be broadcast to all connected clients in real-time.

## Customization

### Changing the Background Color

You can customize the background color of the chat components by modifying the CSS in `ChatComponent.vue`.

```css
.chat-window {
  max-height: 400px;
  overflow-y: auto;
  background-color: #f0f8ff; /* Change this color */
}

.messages {
  height: 300px;
  overflow-y: auto;
  background-color: #fafad2; /* Change this color */
}

b-list-group-item {
  background-color: #e6e6fa; /* Change this color */
  margin-bottom: 5px;
  border-radius: 5px;
}
```


