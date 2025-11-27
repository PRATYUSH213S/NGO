# Cancer Awareness & Support

A responsive single-page website built for internship technical assignment evaluation. This project demonstrates modern web development practices using vanilla HTML, CSS, and JavaScript.

## 📋 Description

This website is designed to raise awareness about cancer and provide a platform for support and communication. It features a beautiful, modern UI with smooth animations, a functional contact form, and real-time motivational quotes to inspire visitors.

## ✨ Features

- **Landing Section**: Inspiring message about cancer awareness with a beautiful banner image and gradient background
- **Donation Dashboard**: Complete donation tracking dashboard with statistics, monthly trends chart, and recent donations table
- **Contact Form**: Fully validated contact form with real-time error checking (Name, Email, Message fields)
- **Motivational Quotes**: Real-time quotes fetched from the Quotable API with a refresh button
- **Responsive Design**: Fully responsive layout that works seamlessly on mobile, tablet, and desktop devices
- **Modern UI**: Clean design with soft violet/purple/blue gradients, rounded cards, subtle shadows, and smooth hover animations
- **Smooth Animations**: Fade-in effects, hover transitions, and smooth scrolling

## 🛠️ Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, gradients, animations, and responsive design
- **Vanilla JavaScript**: Form validation, API integration, and DOM manipulation
- **Google Fonts**: Inter and Poppins font families
- **Quotable API**: For fetching inspirational quotes

## 📁 Project Structure

```
cancer-awareness-support/
│
├── index.html          # Main HTML file with inline CSS and JavaScript
├── README.md           # Project documentation
└── assets/             # Assets directory (for future use)
```

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository
2. **Open `index.html`** directly in your web browser, OR
3. **Use Live Server** in VS Code:
   - Install the "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

### Hosting Options

#### GitHub Pages

1. Create a new GitHub repository named `cancer-awareness-support`
2. Upload all project files to the repository
3. Go to **Settings → Pages**
4. Select branch `main` and root folder `/`
5. Your live site will be available at:
   ```
   https://YOUR_USERNAME.github.io/cancer-awareness-support/
   ```

#### Netlify

1. Drag and drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a random URL
3. You can customize the domain name in settings

#### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

## 🎨 Design Features

- **Color Scheme**: Soft violet (#8B5CF6), purple (#7C3AED), and blue (#6366F1) gradients
- **Typography**: Inter and Poppins fonts for modern, readable text
- **Layout**: Clean, centered design with maximum readability
- **Animations**: Smooth fade-in effects, hover transitions, and interactive elements
- **Responsive Breakpoints**: Optimized for mobile (480px), tablet (768px), and desktop

## 📝 Form Validation

The contact form includes front-end validation for:
- **Name**: Minimum 2 characters
- **Email**: Valid email format (regex validation)
- **Message**: Minimum 10 characters

All fields are required and show real-time error messages.

## 📊 Donation Dashboard

The donation tracking dashboard displays:
- **Total Donations**: Sum of all donations received
- **Number of Donors**: Count of unique donors
- **Average Donation**: Calculated average donation amount
- **Monthly Trends Chart**: Visual bar chart showing donation trends by month
- **Recent Donations Table**: Detailed table with donor names, amounts, and dates

The dashboard uses dummy data with 20 sample donations spanning January to March 2024, demonstrating real-world donation tracking functionality.

## 🔌 API Integration

The website uses the [Quotable API](https://api.quotable.io/) to fetch random inspirational quotes:
- Endpoint: `https://api.quotable.io/random`
- Automatically loads a quote on page load
- Refresh button to fetch new quotes
- Error handling for failed API requests

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Free for educational use.

## 👨‍💻 Development Notes

- All CSS and JavaScript are inline in `index.html` for easy deployment
- No external dependencies required (except Google Fonts and API)
- Fully self-contained and ready to deploy
- Optimized for performance and accessibility

## 🤝 Contributing

This is an internship assignment project. Feel free to use it as a reference or starting point for your own projects.

---

**Built with ❤️ for cancer awareness and support**

