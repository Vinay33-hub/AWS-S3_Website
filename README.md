# AWS-S3_Website
# 🍦 Romyk – Ice Cream Website

A responsive and visually appealing **Ice Cream Website** developed using HTML, CSS, JavaScript, Bootstrap, and hosted on **Amazon S3 Static Website Hosting**.

## 🌐 Live Demo

🔗 **Live Website:** `YOUR_S3_WEBSITE_URL`

> Replace `YOUR_S3_WEBSITE_URL` with your Amazon S3 static website endpoint.

---

## 📌 Project Overview

**Romyk** is a static ice cream website designed to provide users with an attractive interface for exploring ice cream products and services.

The website includes multiple pages such as:

* 🏠 Home
* ℹ️ About
* 🍨 Ice Cream
* 🛎️ Services
* 📝 Blog
* 📞 Contact Us

The website uses a responsive layout and Bootstrap components to provide a better experience across different screen sizes.

---

## ☁️ AWS Deployment

This project is deployed using **Amazon S3 Static Website Hosting**.

### AWS Services Used

* **Amazon S3** – Website hosting and static file storage
* **S3 Bucket Policy** – Allows public access to website objects
* **S3 Static Website Hosting** – Serves the HTML website
* **IAM** – Used for managing AWS permissions

---

## 🛠️ Technologies Used

| Technology   | Purpose               |
| ------------ | --------------------- |
| HTML5        | Website structure     |
| CSS3         | Styling and layout    |
| JavaScript   | Website functionality |
| Bootstrap    | Responsive design     |
| Font Awesome | Icons                 |
| Google Fonts | Typography            |
| Amazon S3    | Cloud hosting         |

The HTML pages load Bootstrap, custom CSS, responsive CSS, Google Fonts, Font Awesome, and JavaScript libraries.

---

## 📂 Project Structure

```text
romyk-icecream-aws-s3/
│
├── index.html
├── about.html
├── icecream.html
├── blog.html
├── contact.html
│
├── css/
│   ├── bootstrap.min.css
│   ├── style.css
│   ├── responsive.css
│   └── jquery.mCustomScrollbar.min.css
│
├── js/
│   ├── jquery.min.js
│   ├── bootstrap.bundle.min.js
│   ├── jquery-3.0.0.min.js
│   ├── plugin.js
│   ├── jquery.mCustomScrollbar.concat.min.js
│   └── custom.js
│
├── images/
│   ├── logo.png
│   ├── banner-img.png
│   ├── about-img.png
│   ├── img-1.png
│   ├── img-2.png
│   ├── img-3.png
│   ├── img-4.png
│   └── img-5.png
│
└── README.md
```

---

## ✨ Features

### 🏠 Home Page

The home page contains:

* Ice cream banner
* Image carousel
* Order Now section
* About section
* Featured ice cream
* Services
* Testimonials
* Contact section

The homepage uses a carousel for multiple banner slides and displays featured ice cream products.

### 🍨 Ice Cream Products

The Ice Cream page displays featured products with:

* Product images
* Product names
* Prices
* Add To Cart buttons

The current page contains several featured ice cream cards priced at `$10`.

### 🛎️ Services

The website provides an **Our Ice Cream Services** section with different ice cream service cards.

### 📝 Blog & Testimonials

The Blog page contains a testimonial carousel with multiple customer testimonial sections.

### 📞 Contact

The Contact Us page provides fields for:

* Name
* Email
* Phone number
* Message
* Newsletter subscription

It also includes social media icons.

---

# 🚀 AWS S3 Deployment

## Step 1 – Create an S3 Bucket

1. Open the AWS Management Console.
2. Go to **Amazon S3**.
3. Click **Create bucket**.
4. Enter your bucket name.
5. Select your AWS Region.
6. Configure the required public-access settings for static website hosting.

---

## Step 2 – Upload Website Files

Upload the complete website structure to your S3 bucket.

Make sure you upload:

```text
index.html
about.html
icecream.html
blog.html
contact.html
css/
js/
images/
```

⚠️ **Important:** Do not upload only the HTML files. Your HTML pages reference files inside the `css`, `js`, and `images` folders, so those folders are required for the website to display correctly.

---

## Step 3 – Enable Static Website Hosting

In your S3 bucket:

**Properties → Static website hosting**

Enable:

```text
Static website hosting: Enabled
Index document: index.html
```

If you have an error document, you can configure:

```text
Error document: error.html
```

---

## Step 4 – Configure Bucket Permissions

Configure the appropriate S3 bucket policy to allow website visitors to read the website objects.

> ⚠️ Never upload AWS Access Keys, Secret Keys, passwords, `.env` files, or other credentials to GitHub.

---

## Step 5 – Test the Website

Open the S3 static website endpoint provided by AWS.

Example:

```text
http://your-bucket-name.s3-website-region.amazonaws.com
```

Your `index.html` page should load as the homepage.

---

# 🔄 Website Navigation

```text
Home
 │
 ├── About
 │
 ├── Icecream
 │
 ├── Services
 │
 ├── Blog
 │
 └── Contact Us
```

The navigation links are implemented using the individual HTML pages such as `index.html`, `about.html`, `icecream.html`, `blog.html`, and `contact.html`.

---

# 📚 What I Learned

Through this project, I gained practical experience with:

* Static website development
* HTML and CSS
* Bootstrap responsive design
* JavaScript integration
* Organizing website assets
* Amazon S3
* Static website hosting
* S3 bucket configuration
* AWS permissions and bucket policies
* Cloud-based website deployment

---

# 🔮 Future Improvements

Possible future enhancements include:

* 🛒 Functional shopping cart
* 💳 Online payment integration
* 🔐 User authentication
* 🗄️ Database integration
* 📱 Improved mobile UI
* 📧 Functional contact form
* 🌐 Custom domain
* 🔒 HTTPS using Amazon CloudFront
* ⚡ CloudFront CDN integration
* 📊 Website analytics

---

# 👨‍💻 Project Information

**Project:** Romyk Ice Cream Website
**Type:** Static Web Application
**Hosting:** Amazon S3
**Frontend:** HTML, CSS, JavaScript, Bootstrap
**Deployment:** AWS S3 Static Website Hosting

---

## ⭐ If you like this project

Feel free to ⭐ **star** this repository and use it as a reference for learning AWS S3 static website hosting.

---

### 📜 License

This project is intended for educational and demonstration purposes.
