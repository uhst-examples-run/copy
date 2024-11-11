# Remote Copy/Paste Using UHST

This project demonstrates how to use the User Hosted Secure Transmission (UHST) framework to securely copy and paste content between devices. You can see a live demo of this project at https://examples.run/copy/.

## Running the Example Locally

### Download the Code

Save the HTML file to a directory on your computer.

### Serve the File Locally

Since UHST requires a server context due to security policies, you need to serve the file using a local web server.

Using Python 3:
```python
python3 -m http.server 8080 --bind 0.0.0.0
```

Using Node.js:
```bash
npx http-server -p 8080
```

### Access the Host Page

Open your web browser and navigate to http://localhost:8080 (or http://127.0.0.1:8080).

### Hosting

* The page will display a Host ID, a QR code, and a shareable link.
* Share the QR code or link with the client device.

By following these steps, you can test the UHST remote copy/paste functionality on your local machine.