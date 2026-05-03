# Cube Classes - Online Tuition Website

🎓 A modern, multi-page website for Cube Classes - offering live online tuition in Maths, Hindi, and Robotics for children aged 5-17.

## Features

✅ Multi-page website (Home, Courses, Mentors, FAQ, Contact)  
✅ Responsive design for mobile & desktop  
✅ JSON-based content management system  
✅ Easy to update without coding  
✅ Professional UI with Tailwind CSS  
✅ SEO-friendly structure  
✅ Built with Next.js 14 & React 18  

## 📁 Project Structure

```
CubeClasses/
├── app/
│   ├── page.tsx              # Homepage
│   ├── courses/
│   │   ├── page.tsx          # All courses
│   │   └── [id]/page.tsx     # Individual course details
│   ├── mentors/page.tsx      # Mentor profiles
│   ├── faq/page.tsx          # FAQ section
│   └── contact/page.tsx      # Contact page
├── components/               # Reusable React components
├── data/
│   ├── config.json          # Company info & hero content
│   ├── courses.json         # Course details & pricing
│   ├── mentors.json         # Mentor profiles
│   ├── testimonials.json    # Student reviews
│   └── faq.json             # FAQ questions & answers
├── public/                  # Images & assets
├── package.json
└── tailwind.config.ts
```

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/ggauravg09/CubeClasses.git
cd CubeClasses
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run Locally
```bash
npm run dev
```
Visit `http://localhost:3000` in your browser.

### 4. Build for Production
```bash
npm run build
npm start
```

## 📝 How to Update Content (No Coding Required!)

All website content is stored in JSON files in the `/data` folder. Simply edit these files:

### Update Company Info
**File:** `data/config.json`
- Company name, email, phone
- Social media links
- Hero section text

### Add/Edit Courses
**File:** `data/courses.json`
- Add new subjects
- Update pricing
- Modify curriculum

### Manage Mentors
**File:** `data/mentors.json`
- Add mentor profiles
- Update qualifications
- Change ratings

### Add Testimonials
**File:** `data/testimonials.json`
- Add student/parent reviews
- Update ratings

### Update FAQ
**File:** `data/faq.json`
- Add/edit questions and answers

## 🎨 Customization

### Change Brand Colors
Edit `tailwind.config.ts`:
```javascript
theme: {
  extend: {
    colors: {
      primary: '#your-color',
      secondary: '#your-color'
    }
  }
}
```

### Add Logo
Replace the emoji icon in header with your logo file in `/public` folder.

### Update Favicon
Add `favicon.ico` to `/public` folder.

## 🌐 Deployment

### Deploy to Vercel (Recommended)
1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "Import Project"
4. Select your GitHub repository
5. Click "Deploy"

**It's that simple!** Vercel will automatically deploy your site.

### Connect Custom Domain
1. In Vercel dashboard, go to Settings → Domains
2. Add your custom domain (e.g., cubeclasses.com)
3. Update DNS settings at your domain provider

## 📅 Development Roadmap

- [x] Multi-page website structure
- [x] Course listing and details
- [x] Mentor profiles
- [x] Testimonials section
- [x] FAQ section
- [ ] Free demo class booking system
- [ ] Payment gateway integration (Stripe/Razorpay)
- [ ] Student login & dashboard
- [ ] AI learning assistant (Cubo)
- [ ] Blog/Resources section
- [ ] WhatsApp integration
- [ ] Email notifications

## 🤝 Support

For questions or support, contact: contact@cubeclasses.com

## 📄 License

MIT License - Feel free to use this template for your business.

---

**Built with ❤️ for Cube Classes**
