# Magento 2 Google Indexing API

The Magento 2 Google Indexing API extension is an SEO tool that streamlines the indexing process by automatically notifying Google when a new or updated webpage is available. This speeds up the process of getting your content indexed, ensuring better visibility in search results.

## **How Magento 2 Google Indexing API Extension Works?**

The extension integrates with the Google Indexing API to automatically send indexing requests to Google when content is updated or new pages are added. It supports both automatic and manual submission of URLs for indexing, ensuring that key pages are prioritized for crawling. Additionally, you can manage indexing requests in bulk and monitor their status for enhanced control over SEO performance.

## **Key Features of Google Indexing API for Magento 2**

* **Automatic Indexing Requests:** Automatically notify Google when content is updated or new pages are added.  
* **Manual Indexing Submissions:** Manually submit pages or products for indexing with a single click.  
* **Bulk Indexing Requests:** Submit multiple URLs or upload a list for bulk indexing.  
* **Customizable Page Types:** Choose which pages (e.g., CMS, products) should be indexed automatically.  
* **Indexing Request Logs:** Track and manage indexing requests, including status updates for all submitted URLs.  
* **Google Search Console Integration:** Requires Google Search Console for API authentication and configuration.

The Magento 2 Google Indexing API Extension offers a comprehensive set of features designed to enhance the indexing process for your online store, ensuring that your pages are quickly and efficiently indexed by Google. Here are the detailed key features:

## Integration with Google Indexing API:

![Integration with Google Indexing API](https://github.com/user-attachments/assets/6ba144f8-5fdc-4a68-8c46-58c4931acc6a)

The extension seamlessly integrates with Google’s Indexing API, allowing your Magento store to communicate directly with Google for faster indexing of web pages.

## Automatic Indexing Requests:

![Automatic Indexing Requests](https://github.com/user-attachments/assets/5ac7e25f-09b3-4977-a5ee-2576d7f7dc28)

Once configured, the extension automatically sends indexing requests to Google whenever specific attributes of your content (like product details or CMS page updates) are changed. This ensures that updates are reflected in search results without manual intervention.

## Bulk URL Submission:

![Bulk URL Submission](https://github.com/user-attachments/assets/62ad2e3b-19c7-4930-85d1-c2014c5b4a96)

Users can submit multiple URLs for indexing at once. This feature allows for efficient management of indexing requests by entering URLs directly or uploading a text file containing multiple URLs.

## Manual Submission Options:

![Manual Submission Options](https://github.com/user-attachments/assets/8f5569c0-fff9-4d8e-b6cd-bdd6caf88226)

In addition to automatic requests, users can manually submit individual pages or products for indexing. This is facilitated through a "Request Google Indexing" option available in the Magento admin panel for each page.

## Indexing Schedule Log Management:

![Indexing Schedule Log Management](https://github.com/user-attachments/assets/b35abcea-a33e-4f6d-b029-0ad29e19e3db)

The extension includes a feature that allows users to manage the lifetime of logs related to indexing requests. Users can set a retention period after which old logs will be automatically cleared, helping maintain an organized system.

## User-Friendly Interface:

The extension is designed with ease of use in mind. It provides an intuitive interface within the Magento admin panel where users can configure settings, submit URLs, and view logs without needing extensive technical knowledge.

These features collectively enhance the visibility and ranking potential of your Magento store's content on search engines by ensuring timely indexing and management of web pages.

## Extension Installation

To install the Magento 2 Google Indexing API Extension, follow these steps:

### Step 1

Install the Google API library using SSH:

composer requires Google/apiclient

### Step 2

Download and extract the extension zip file to your Magento root directory.

### Step 3

Run the following commands step by step:

php bin/magento setup:upgrade  
php bin/magento setup:static-content:deploy –f  
php bin/magento cache:flush

## Steps to Configure Magento 2 Google Indexing API Extension

To set up the Magento 2 Google Indexing API Extension, follow these configuration steps:

### Step 1\. API Integration:

![API Integration](https://github.com/user-attachments/assets/33372864-e1e3-435a-b2e9-1aed8d1db497)

* Navigate to Stores \> Configuration \> Meetanshi \> Google Indexing API.  
  * Change the extension status to enabled.  
  * Set a request delay (in minutes) between each indexing request to avoid hitting API limits.  
  * Upload the JSON key file downloaded from your Google Cloud Console.

### Step 2\. Automatic Indexing Settings:

![Automatic Indexing Settings](https://github.com/user-attachments/assets/91b4fc29-0ba5-44fa-9298-33c9154d29d9)

* Enable automatic indexing requests on content updates by setting it to "Yes".  
  * Choose which types of pages will trigger automatic requests (CMS, product, category).  
  * Specify product attributes that should trigger indexing when updated.

### Step 3\. Set Requests Log Lifetime:

![Set Requests Log Lifetime](https://github.com/user-attachments/assets/6279bac2-83a6-4524-92e4-12c9a0c811ac)

Manage storage for indexing request logs by setting a lifetime (in days) after which logs will be automatically cleared.

### Step 4\. Manual Request Submission:

![Manual Request Submission](https://github.com/user-attachments/assets/4a4f9ebf-6b88-4b0a-a39e-eeb48ab8dde7)

To submit products or pages for indexing manually, use the "Request Google Indexing" option in the edit sections of products or pages.

For bulk submissions, navigate to Content \> Google Indexing API \> Manual Request Submission and enter URLs or upload a text file.

### Step 5\. Monitor Indexing Requests:

![Monitor Indexing Requests](https://github.com/user-attachments/assets/8ec59205-8dcb-4b57-b3c4-d30b6a1fc5e4)

View statuses of both manual and automated requests through Content \> Google Indexing API \> Request Log, where you can track URL actions, statuses, and execution times.

By following these steps, you can effectively configure and utilize the Magento 2 Google Indexing API Extension to enhance your website's SEO performance.

## Download our Magento 2 Google Indexing API Extension: 

[https://meetanshi.com/magento-2-google-indexing-api.html](https://meetanshi.com/magento-2-google-indexing-api.html)
