# Cloudinary Uploader – Firebase Storage Alternative (Free!)
[![Watch Demo](https://img.youtube.com/vi/kOLG66Osdb8/0.jpg)](https://youtu.be/kOLG66Osdb8)

A modern Android example project using **Cloudinary** as a free alternative to Firebase Storage.  
Built with **Material 3 UI**, **Scoped Storage**, and **Storage Access Framework (SAF)** – fully compatible with **API 24 to 35**.

## Features

- Upload media files (images, videos, audio, and raw files) to Cloudinary
- Delete files using their `public_id`
- Cancel uploads in-progress
- File picker via Storage Access Framework (no permissions required)
- Clean Material 3 design (Day/Night theme supported)

## Why Cloudinary?

Cloudinary's free plan offers generous limits for small-to-medium apps:

- **Total Storage**: 25 GB managed storage  
- **Monthly Credits**: 25  
  - 1 GB of storage = 1 credit  
  - 1 GB of bandwidth = 1 credit  
  - 1,000 transformations = 1 credit  
- **Maximum File Size**:  
  - Images: 10 MB  
  - Videos: 100 MB  
  - Raw Files (PDF, ZIP): 10 MB  
  - Audio: 100 MB  

## Android Storage Model

This project uses **Scoped Storage** and **SAF**, meaning:

- No need for `READ_EXTERNAL_STORAGE` or `WRITE_EXTERNAL_STORAGE` permissions
- Files are selected using the system file picker
- Fully Play Store compliant

## Tech Stack

- **Language**: Java
- **UI**: Material 3 (M3) with dynamic theming
- **Storage Picker**: SAF
- **Cloud Storage**: Cloudinary REST API (upload, delete)

## Setup

1. Create a free Cloudinary account at [cloudinary.com](https://cloudinary.com/)
2. Get your `Cloud Name`, `API Key`, and `API Secret`
3. Add your credentials in the project (securely)
4. Run the app and start uploading files with no permission hassle
---

**Note**: This project is built for educational/demo purposes but can be scaled for production with proper authentication and media management strategies.
