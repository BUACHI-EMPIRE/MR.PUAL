# 🔐 Secure File & Text Encryption Tool

A modern, client-side encryption application built with HTML5, CSS3, and JavaScript that provides military-grade encryption for files and text messages. All encryption happens locally in your browser - your data never leaves your device.

## ✨ Features

### 🔒 **Core Encryption**
- **Military-grade encryption** using AES-256 and other advanced algorithms
- **Client-side processing** - no data sent to external servers
- **Multiple encryption algorithms**: AES-GCM, AES-CBC, AES-CTR, ChaCha20-Poly1305
- **File support** up to 50MB with drag & drop functionality
- **Text encryption** for secure messaging and notes

### ⚙️ **Advanced Configuration**
- **Customizable key sizes**: 128-bit, 192-bit, 256-bit
- **Key Derivation Functions**: PBKDF2, Argon2, bcrypt, scrypt
- **Hash functions**: SHA-256, SHA-384, SHA-512, BLAKE2b
- **Configurable iterations** (1,000 - 1,000,000)
- **Custom salt and IV lengths**
- **Use case presets** for different security requirements
- **Security level presets** from standard to post-quantum ready

### 🎨 **User Experience**
- **Modern, responsive design** that works on all devices
- **Dark/Light theme toggle** with persistent preferences
- **Drag & drop file upload** with visual feedback
- **Real-time status updates** and error handling
- **File preview** for text-based files
- **Download functionality** for both encrypted and decrypted files

### 📚 **Educational Features**
- **Comprehensive learning section** about encryption concepts
- **Step-by-step usage guides** for encryption and decryption
- **Security best practices** and recommendations
- **Common use cases** and practical examples
- **Tips and tricks** for optimal security

## 🚀 Getting Started

### **Prerequisites**
- Modern web browser with Web Crypto API support
- No installation required - runs entirely in the browser

### **Browser Compatibility**
- ✅ Chrome 37+ (2014)
- ✅ Firefox 34+ (2014)
- ✅ Safari 11+ (2017)
- ✅ Edge 12+ (2015)
- ❌ Internet Explorer (not supported)

### **Quick Start**
1. **Download** the `index.html` file
2. **Open** it in your web browser
3. **Start encrypting** files and text immediately!

## 📖 Usage Guide

### **🔒 Encrypting Data**

#### **File Encryption**
1. **Upload a file** by dragging and dropping or clicking to browse
2. **Enter a strong password** (recommended: 12+ characters)
3. **Choose encryption algorithm** (AES-GCM recommended)
4. **Configure advanced settings** (optional)
5. **Click "Encrypt"** to process your file
6. **Download the encrypted file** as a JSON file

#### **Text Encryption**
1. **Type your message** in the text area
2. **Enter a strong password**
3. **Configure encryption settings**
4. **Click "Encrypt"**
5. **Copy or download** the encrypted data

### **🔓 Decrypting Data**

#### **From Encrypted File**
1. **Load the encrypted JSON file** using "Load File" button
2. **Or paste the encrypted data** directly
3. **Enter the original password**
4. **Click "Decrypt"**
5. **View or download** the decrypted content

#### **From Pasted Data**
1. **Paste the encrypted JSON** into the text area
2. **Enter the password**
3. **Click "Decrypt"**
4. **Access your data**

## 🛡️ Security Features

### **Encryption Standards**
- **AES-256** as the default encryption algorithm
- **PBKDF2** for secure key derivation
- **Random salt generation** for each encryption
- **Unique IVs** for each encryption operation
- **Authenticated encryption** with AES-GCM

### **Security Best Practices**
- **Strong password requirements** (8+ characters minimum)
- **High iteration counts** (100,000+ recommended)
- **Random salt generation** (16+ bytes)
- **Secure key derivation** with configurable parameters
- **No data transmission** to external servers

### **Privacy Protection**
- **100% client-side processing**
- **No data logging** or storage
- **No network requests** for encryption/decryption
- **Local file handling** only

## ⚙️ Advanced Configuration

### **Algorithm Selection**
- **AES-GCM**: Authenticated encryption (recommended)
- **AES-CBC**: Cipher block chaining
- **AES-CTR**: Counter mode for parallel processing
- **ChaCha20-Poly1305**: Modern stream cipher

### **Key Derivation Settings**
- **PBKDF2**: Password-based key derivation
- **Iterations**: 1,000 - 1,000,000 (higher = stronger)
- **Salt length**: 8 - 64 bytes
- **Hash functions**: SHA-256, SHA-384, SHA-512, BLAKE2b

### **Security Presets**
- **Standard**: 128-bit keys, 50k iterations
- **High**: 256-bit keys, 100k iterations
- **Military**: 256-bit keys, 200k iterations
- **Post-Quantum**: 256-bit keys, 500k iterations

## 📁 File Support

### **Supported File Types**
- **All file types** (binary and text)
- **Maximum size**: 50MB (configurable)
- **Text files**: Preview available
- **Binary files**: Download only

### **File Handling**
- **Drag & drop** support
- **Click to browse** alternative
- **File information** display
- **Size and type** validation
- **Automatic format** detection

## 🎨 Customization

### **Theme Options**
- **Dark theme** (default)
- **Light theme** option
- **Persistent preferences** stored locally
- **Smooth transitions** between themes

### **Responsive Design**
- **Mobile-first** approach
- **Adaptive layouts** for all screen sizes
- **Touch-friendly** interface
- **Optimized spacing** for mobile devices

## 🔧 Technical Details

### **Architecture**
- **Single-page application** (SPA)
- **Vanilla JavaScript** (no frameworks)
- **CSS Grid and Flexbox** for layouts
- **Web Crypto API** for cryptographic operations
- **Local Storage** for theme preferences

### **Cryptographic Implementation**
- **Web Crypto API** for all cryptographic operations
- **ArrayBuffer** handling for binary data
- **Base64 encoding** for JSON serialization
- **Error handling** with try-catch blocks
- **Input validation** for security

### **Performance Optimizations**
- **Asynchronous operations** for large files
- **Efficient memory usage** with streaming
- **Optimized Base64 conversion** for large data
- **Debounced input handling** for real-time updates

## 📚 Learning Resources

### **Encryption Concepts**
- **What is encryption** and how it works
- **Types of encryption** algorithms
- **Key concepts** (keys, salt, IV, KDF)
- **Security best practices**

### **Usage Tutorials**
- **Step-by-step encryption** guide
- **Step-by-step decryption** guide
- **Advanced configuration** tips
- **Troubleshooting** common issues

### **Security Guidelines**
- **Password creation** best practices
- **File organization** strategies
- **Backup and recovery** procedures
- **Common security** pitfalls to avoid

## 🚨 Security Considerations

### **Important Notes**
- **Password security** is your responsibility
- **Lost passwords** cannot be recovered
- **Encrypted files** are only as secure as your password
- **Regular backups** of encrypted data recommended

### **Best Practices**
- **Use strong, unique passwords** for each encryption
- **Store passwords securely** (password manager recommended)
- **Backup encrypted files** to multiple locations
- **Test decryption** before deleting originals
- **Keep software updated** for security patches

## 🐛 Troubleshooting

### **Common Issues**
- **"Maximum call stack size exceeded"**: File too large, reduce size
- **"Decryption failed"**: Check password and file integrity
- **"Invalid format"**: Ensure encrypted data is complete JSON
- **"File too large"**: Use files under 50MB limit

### **Solutions**
- **Verify password** spelling and case
- **Check file integrity** (no corruption during transfer)
- **Use supported browsers** with Web Crypto API
- **Clear browser cache** if experiencing issues

## 🔄 Version History

### **v2.0 (Current)**
- **Complete redesign** with modern UI/UX
- **Advanced configuration** options
- **Comprehensive learning** section
- **Enhanced security** features
- **Mobile-responsive** design

### **v1.0 (Previous)**
- **Basic encryption** functionality
- **Simple interface** design
- **Limited configuration** options

## 🤝 Contributing

### **Development Setup**
1. **Clone** the repository
2. **Open** `index.html` in a browser
3. **Make changes** to HTML, CSS, or JavaScript
4. **Test** functionality thoroughly
5. **Submit** pull request with detailed description

### **Code Standards**
- **Semantic HTML** structure
- **CSS custom properties** for theming
- **ES6+ JavaScript** features
- **Responsive design** principles
- **Accessibility** considerations

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Web Crypto API** for cryptographic functionality
- **Modern CSS** features for responsive design
- **Browser vendors** for Web Crypto API support
- **Open source community** for inspiration and tools

## 📞 Support

### **Getting Help**
- **Check troubleshooting** section above
- **Review usage guide** for step-by-step instructions
- **Verify browser compatibility** requirements
- **Test with simple text** before encrypting files

### **Feature Requests**
- **Submit issues** through GitHub
- **Describe use case** and requirements
- **Provide examples** of desired functionality
- **Consider security implications** of new features

---

**🔒 Remember: Your security is in your hands. Use strong passwords and keep them safe!**

*Built with ❤️ for secure, private communication and data protection.*
