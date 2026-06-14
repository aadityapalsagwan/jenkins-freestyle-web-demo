# Jenkins Freestyle Web Demo

A simple static website project demonstrating Jenkins Freestyle Job integration with GitHub.

## Features

- HTML5 webpage
- Responsive CSS styling
- JavaScript interaction
- Jenkins Freestyle CI/CD pipeline
- GitHub integration

## Project Structure

```text
simple-webpage/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Jenkins Configuration

### Source Code Management

Repository URL:

```bash
https://github.com/aadityapalsagwan/jenkins-freestyle-web-demo.git
```

### Build Step

Execute Shell:

```bash
echo "Starting Build..."
pwd
ls -la
echo "Build Successful!"
```

### Optional Deployment

```bash
sudo cp -r * /var/www/html/
```

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Jenkins
- GitHub

## Author

Aaditya Pal

## License

MIT License