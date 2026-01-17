# PowerFit Gym Website

A modern, responsive gym website built with Flask and featuring a sleek dark theme design. This project showcases a complete gym business website with information about facilities, trainers, and membership plans.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-3.0.0+-000000?style=flat&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 🌟 Features

### Homepage
- **Hero Section** with compelling tagline and call-to-action buttons
- **Live Statistics**: 5000+ members, 50+ trainers, 100+ weekly classes
- **6 Core Features**:
  - Premium Equipment
  - Expert Trainers
  - Flexible Classes
  - Recovery Zone (spa, sauna, steam rooms)
  - Nutrition Bar
  - Smart Mobile App
- **Photo Gallery** showcasing gym facilities
- **Special Offer**: 50% off first month promotion

### About Us Page
- Company origin story (founded 2010)
- Core values: Excellence, Community, Innovation, Inclusivity
- Meet the team section with 4 featured trainers
- Detailed facilities information

### Membership Page
- **3 Pricing Tiers**:
  - Basic ($29/month): Gym floor + cardio access
  - Pro ($59/month): All classes + 2 PT sessions
  - Elite ($99/month): Full access + pool/spa + 4 PT sessions
- **Premium Services**:
  - Personal Training
  - Nutrition Coaching
  - Fitness Assessment
  - Group Training
- **Group Classes Schedule**: HIIT, Yoga, Spin Cycle, and more

## 🎨 Design Features

- Modern, responsive design with CSS Grid and Flexbox
- Dark theme with purple/orange gradient accents
- Custom CSS variables for easy theming
- Font Awesome icons
- Smooth animations and transitions
- Professional Unsplash photography
- Mobile-optimized navigation

## 🛠️ Technologies Used

### Backend
- **Flask 3.0.0+** - Python web framework
- **Jinja2** - Template engine (included with Flask)
- **Python 3.x** - Programming language

### Frontend
- **HTML5** - Markup structure
- **CSS3** - Custom styling with modern features
  - CSS Variables
  - Grid & Flexbox layouts
  - Smooth animations
- **Google Fonts** - Inter font family
- **Font Awesome 6.5.1** - Icon library

## 📋 Prerequisites

- Python 3.x installed on your system
- pip (Python package manager)

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/muneebusmani/gym-site.git
   cd gym-site
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Open your browser**
   Navigate to `http://127.0.0.1:5000` or `http://localhost:5000`

## 📁 Project Structure

```
gym-site/
│
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
│
├── static/
│   └── styles.css        # Custom CSS styling (~1000+ lines)
│
└── templates/
    ├── index.html        # Homepage
    ├── about.html        # About Us page
    └── membership.html   # Membership plans page
```

## 🔧 Configuration

The Flask app runs in debug mode by default. To change this, modify `app.py`:

```python
if __name__ == '__main__':
    app.run(debug=False)  # Set to False for production
```

## 🎯 Routes

- `/` - Homepage
- `/about` - About Us page
- `/membership` - Membership plans and pricing

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1920px and above)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🎨 Color Scheme

```css
Primary: #6366f1 (Indigo)
Secondary: #f97316 (Orange)
Accent: #22d3ee (Cyan)
Dark: #0f172a (Slate)
```

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Muneeb Usmani**
- GitHub: [@muneebusmani](https://github.com/muneebusmani)

## 🙏 Acknowledgments

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Fonts from [Google Fonts](https://fonts.google.com)

## 🚧 Future Enhancements

- [ ] Contact form with email functionality
- [ ] Member login/registration system
- [ ] Class booking system
- [ ] Payment integration
- [ ] Admin dashboard
- [ ] Blog section
- [ ] Interactive class schedule calendar
- [ ] Member testimonials
- [ ] Live chat support

## 📞 Contact

For any questions or feedback, please reach out:
- Email: info@powerfit.com
- Phone: (555) 123-4567
- Address: 123 Fitness Street, City

---

**Made with ❤️ for fitness enthusiasts**
