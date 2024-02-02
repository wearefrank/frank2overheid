API Repository Readme
Overview

Welcome to the API repository! This repository contains various APIs, each with its own set of links and tests. Some of these APIs require certificates for secure communication. This readme provides instructions on obtaining and installing the necessary certificate for the APIs from KVK.
Certificate Installation

If you are accessing APIs from KVK, you need a root certificate to establish a secure connection. Follow the steps below to download and install the required certificate:

    Download Certificate:
        Obtain the root certificate from KVK by visiting the following link: PrivateRootCA-G1.cer.

    Create cacerts Folder:
        Ensure you have a "cacerts" folder in your frank runner. If it doesn't exist, create one in the root directory of your frank runner.

    Place Certificate:
        Move the downloaded certificate (PrivateRootCA-G1.cer) into the "cacerts" folder.

    Verify Installation:
        Double-check that the certificate is correctly placed in the "cacerts" folder.

API Usage

With the certificate installed, you can now confidently make secure API calls to KVK APIs. Make sure your frank runner is configured to use the "cacerts" folder.
Additional Notes

    If you encounter any issues with the certificate or API connections, revisit the installation steps to ensure everything is set up correctly.

    For any specific API usage details, refer to the documentation provided with each API.

Feel free to explore the various APIs in this repository and reach out if you have any questions or concerns. Happy coding!
