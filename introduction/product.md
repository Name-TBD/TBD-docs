># Product

**RentHub** offers a streamlined, intuitive platform built on the pre-deployed BTFS infrastructure, allowing users to easily upload files and rent BTFS nodes. The core functionality of RentHub revolves around simplifying the process of interacting with BTFS, providing both a user-friendly dashboard and an SDK for seamless integration into projects.

## Core Functionality
RentHub’s main value lies in its ability to remove the complexity of managing a BTFS node. Users can rent nodes and upload their files effortlessly. RentHub offers:
- **Seamless File Uploads**: Whether through the dashboard or SDK, the file upload process is fast and intuitive.
- **File Management**: Track and manage your files, including setting expiration dates for how long files are stored.

## Main Components
1. **SDK**: The SDK is at the heart of RentHub’s ease of use. With simple function calls in TypeScript or JavaScript, users can integrate BTFS technology into their own projects without any heavy lifting.
   
2. **Dashboard**: Similar to using Google Drive, the RentHub dashboard allows users to drag and drop files for easy uploading to BTFS. Additionally, users can monitor the validity and storage period of their files through this interface.

## File Upload Process
- **Via Dashboard**: The experience is just like uploading files to any cloud storage service. Drag and drop the file, and it’s uploaded to BTFS.
- **Via SDK**: A simple function call in your project’s code triggers the file upload, making it as convenient as possible for developers.

## Subscription Model
While the exact pricing for file uploads based on file size and rental periods is still being refined, RentHub currently operates on a base price of 1,000 credits. This pricing model will evolve as usage patterns and file sizes are better understood.

## Additional Tools
RentHub provides comprehensive documentation (like this!) alongside the main website, which includes the dashboard for file management. The personalized SDK simplifies the technical aspects of integrating BTFS.

## Security Measures
RentHub prioritizes security by masking user identities through the rented BTFS nodes. Additionally, industry-standard security protocols are implemented to safeguard user data and ensure only authorized usage of the platform.

## Scalability
Currently, RentHub operates using a single BTFS node, which may present scalability challenges as the user base grows. However, future plans include implementing a node balancer approach using Kubernetes to scale as demand increases, ensuring smooth and uninterrupted service.
