# Better-Github

A modern, responsive GitHub profile viewer with enhanced UI and real-time data fetching capabilities.

## Features

- Clean, dark-themed interface
- Real-time GitHub profile data visualization
- Responsive design for all screen sizes
- Repository showcase with key metrics
- Profile statistics dashboard
- Animated transitions and hover effects

## Demo

Try it out:
1. Visit the homepage
2. Enter any GitHub username
3. View the enhanced profile page

Or view a sample profile directly at `api.html?username=a-TechyBoy`

## Technical Details

### Technologies Used
- HTML5
- CSS3 (with modern animations)
- Vanilla JavaScript
- GitHub REST API
- Font Awesome icons
- Google Fonts

### API Integration
The application uses the GitHub API endpoints:
- `/users/{username}` for profile data
- `/users/{username}/repos` for repository information

### Key Components

#### Profile Section
- Profile image with hover effects
- User statistics (followers, following, repositories)
- Contact information
- Bio and location details

#### Repository Display
- Repository cards with descriptions
- Language indicators
- Star counts
- Hover animations

## Installation

1. Clone the repository
2. Open `index.html` in a web browser
3. No build process or dependencies required

## Usage

```
https://your-domain.com/api.html?username={github-username}
```

Replace `{github-username}` with any valid GitHub username.

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to submit issues and pull requests for additional features or improvements.

## License

MIT License - Feel free to use and modify for your own projects.