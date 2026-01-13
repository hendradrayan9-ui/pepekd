<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot UI</title>
    <script src="https://cdn.jsdelivr.net/npm/@digitalocean/agents-chat-widget@latest"></script>
</head>
<body>
    <div id="chatbot-container"></div>
    <script>
        const chatbot = new AgentChatWidget({
            // Ganti dengan ID Chatbot yang kamu punya
            endpoint: "https://acazz6js52pbhgtmykkodxmo.agents.do-ai.run/v1/n3b06LChLMsGpUBExD0cwR82ohWFpH-f/run",
            container: "#chatbot-container", 
            title: "Chat with us"
        });

        chatbot.init();
    </script>
</body>
</html>
