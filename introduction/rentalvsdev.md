># Rental or Dev

To streamline the development process, RentHub offers two distinct modes for uploading files: **Rental** and **Dev**. This allows users to easily test their integrations in a development environment before transitioning to the full-fledged rental mode for live deployments.

## **Rental Mode**
In **Rental Mode**, files are uploaded to BTFS in the traditional way, where users define the file and specify the duration for which it will be deployed. These files are stored on the BTFS network and can be accessed via the BTFS gateway, making them publicly available and securely pinned for the duration you specify.

Key features of **Rental Mode**:
- **Set Duration**: Define how long your files will remain available on BTFS.
- **Permanent Availability**: Files are accessible via BTFS gateways for the entire rental period.
- **Cost**: Uploads in rental mode will deduct credits based on file size and duration.

## **Dev Mode**
In contrast, **Dev Mode** is designed for testing and development. Files uploaded in **Dev Mode** are temporary and will be cleared by the node’s garbage collector after a specific duration. This mode is ideal for testing file uploads during development, as the files remain accessible for a limited time before being automatically deleted.

Key features of **Dev Mode**:
- **Temporary Files**: Files uploaded will only be available until the node’s garbage collector clears them.
- **Testing Phase**: This mode allows you to ensure your RentHub integration works in your project before shifting to Rental Mode.
- **Cost-Free**: Uploads in **Dev Mode** do not deplete credits, as files are uploaded directly to the node without any cost.

**Note**: Files in Dev Mode are accessible via a unique URL provided for each specific file. This URL is valid until the garbage collector clears the file, giving you enough time for testing.

