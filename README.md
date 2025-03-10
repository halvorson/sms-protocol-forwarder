# SMS Protocol Forwarder

This project is designed to facilitate the forwarding of SMS messages through a simple HTML webpage. It takes URL parameters and automatically redirects users to the `sms://` protocol, allowing for easy SMS composition directly from a web link.

## Purpose

The SMS Protocol Forwarder enables users to create links that, when clicked, will open the default SMS application on their device with pre-filled recipient numbers and message content. This is particularly useful for websites or applications that want to provide a quick way for users to send SMS messages.

## How to Use

1. **Set Up the Project**: Clone or download the repository to your local machine.
2. **Open the `index.html` File**: Navigate to the `src` directory and open the `index.html` file.
3. **Create a Link**: To use the SMS Protocol Forwarder, create a link with the following format:
   ```
   http://yourdomain.com/sms-protocol-forwarder/src/index.html?phone=1234567890&message=Hello%20World
   ```
   Replace `1234567890` with the desired phone number and `Hello%20World` with the desired message. Make sure to URL-encode the message.

4. **Access the Link**: When the link is accessed, the webpage will read the URL parameters and redirect to the SMS application with the specified phone number and message.

## Example

To send a message "Hello, how are you?" to the number 9876543210, the link would look like this:
```
http://yourdomain.com/sms-protocol-forwarder/src/index.html?phone=9876543210&message=Hello,%20how%20are%20you?
```

## License

This project is open-source and available for anyone to use and modify.