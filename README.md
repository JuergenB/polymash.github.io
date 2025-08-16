# YouTube Script Agent for Artist Profiles

An automated AI-powered workflow that transforms artist profile information into professional YouTube content, complete with scripts and audio generation.

## 🎯 What It Does

This intelligent agent automatically:

1. **Scrapes Artist Data** - Extracts comprehensive information from artist profile pages, including biography, artist statements, and artwork details
2. **Enhances with Website Content** - Visits artist websites and social media to gather additional biographical information from dedicated about pages
3. **Generates AI-Powered Content** - Creates professional artist profiles and 3-minute YouTube scripts using advanced AI
4. **Produces Audio Content** - Converts scripts to professional voiceover audio using Wondercraft.ai
5. **Delivers Complete Package** - Emails all content and saves audio files to Google Drive with permanent links

## 🚀 Features

### Intelligent Web Scraping
- **Multi-source data collection** from artist profiles, personal websites, and social media
- **Smart about page detection** - Automatically finds and scrapes `/about`, `/bio`, and `/story` pages
- **Artwork analysis** - Processes 1-3 key artworks with detailed descriptions
- **Social media integration** - Extracts Instagram and website links with formatted CTAs

### AI-Powered Content Generation
- **Comprehensive artist profiles** combining all scraped data
- **Professional YouTube scripts** optimized for 3-minute videos
- **Exhibition context integration** - Connects artist work to curatorial themes
- **Spoken-friendly formatting** - URLs formatted for natural speech (e.g., "example dot com")

### Professional Audio Production
- **Wondercraft.ai integration** for high-quality text-to-speech
- **Job monitoring** with automatic completion detection
- **Google Drive storage** with permanent download links
- **Email delivery** of complete content packages

### Memory-Optimized Performance
- **Cost-effective operation** without requiring increased memory limits
- **Efficient data processing** with smart cleanup and optimization
- **Reliable execution** designed for consistent performance

## 🌐 Public Access

**Live Form:** [https://juergenb.github.io/polymash.github.io/youtube-script-generator.html](https://juergenb.github.io/polymash.github.io/youtube-script-generator.html)

Anyone can submit artist information through the public form to generate YouTube content automatically.

## 🛠 Technical Architecture

### Built on Pipedream Platform
- **HTTP Webhook Trigger** - Accepts form submissions from public website
- **10-Step Automated Workflow** - Fully orchestrated content generation pipeline
- **Multiple API Integrations** - OpenAI, Wondercraft.ai, Google Drive, Gmail
- **Browser Automation** - Puppeteer-powered web scraping

### Workflow Steps
1. **Extract User Inputs** - Process form data (artist name, profile URL, exhibition theme)
2. **Scrape Artist Profile** - Extract biography, statement, and artwork links
3. **Extract Website & Social Links** - Find and scrape artist websites and social media
4. **Scrape Artwork Details** - Gather detailed information about individual artworks
5. **Create Artist Profile** - AI-generated comprehensive artist analysis
6. **Generate YouTube Script** - Professional 3-minute video script with CTAs
7. **Create Wondercraft Audio** - Upload script for professional voiceover generation
8. **Monitor Job Completion** - Poll until audio generation is complete
9. **Save to Google Drive** - Store MP3 file with permanent access
10. **Send Final Email** - Deliver complete content package

## 📋 Input Requirements

- **Artist Name** - Full name of the featured artist
- **Artist Profile URL** - Link to artist's profile page or portfolio
- **Exhibition Theme** - Curatorial context or exhibition description

## 📦 Output Delivered

### Email Package Contains:
- **Comprehensive Artist Profile** - Biography, statement, and artwork analysis
- **Professional YouTube Script** - 3-minute voiceover-ready content
- **Artist Website & Social Media Info** - Links and additional biographical content
- **Google Drive Audio File** - Professional MP3 with permanent download link
- **Exhibition Context** - How the artist's work relates to the theme

### File Storage:
- **Google Drive Integration** - Permanent cloud storage
- **Organized File Naming** - "Artist Name - YouTube Script Audio.mp3"
- **Shareable Links** - Direct access for content creators

## 🎨 Perfect for Art Organizations

This tool is ideal for:
- **Art Nonprofits** creating educational content about emerging artists
- **Galleries** producing promotional videos for exhibitions
- **Curators** developing artist spotlights and features
- **Art Educators** creating instructional content about contemporary artists
- **Content Creators** in the art space needing professional scripts and audio

## 🔧 Setup & Configuration

### Required Integrations:
- **OpenAI Account** - For AI content generation
- **Wondercraft.ai Account** - For professional audio generation
- **Google Drive** - For file storage
- **Gmail** - For content delivery

### Environment Variables:
- Wondercraft API Key
- Voice ID for audio generation
- Google Drive folder configuration
- Email delivery settings

## 🚀 Getting Started

1. **Access the Public Form** - Visit the live form URL
2. **Submit Artist Information** - Provide artist name, profile URL, and exhibition theme
3. **Wait for Processing** - Workflow typically completes in 3-5 minutes
4. **Receive Email** - Complete content package delivered automatically
5. **Access Audio File** - Download MP3 from Google Drive link

## 🤝 Contributing

This project was built to support art nonprofits and organizations working with emerging artists. Contributions and improvements are welcome!

## 📄 License

Built for educational and nonprofit use in supporting emerging artists and art organizations.

---

**Powered by Pipedream • OpenAI • Wondercraft.ai • Google Drive**
