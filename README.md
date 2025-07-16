COMPANY: CODTECH IT SOLUTIONS

NAME: Guntamadugu Tharun 

INTERN ID: CT06DH1622

DOMAIN: Full Stack Web Development

DURATION: 6 WEEEKS

MENTOR:NEELA SANTOSH

# Weather Dashboard 🌤️

A responsive weather application that fetches and displays real-time weather data from the OpenWeatherMap API. Built with vanilla HTML, CSS, and JavaScript.

## Features

- **Real-time Weather Data**: Current weather conditions for any city worldwide
- **5-Day Forecast**: Extended weather forecast with daily predictions
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Search**: Search by city name with Enter key support
- **Modern UI**: Glassmorphism design with smooth animations and hover effects
- **Error Handling**: Graceful fallback to demo data when API is unavailable
- **Loading States**: Visual feedback during data fetching

## Demo

The application loads with demo data for London by default. You can search for any city to see live weather data (requires API key setup).

## Technologies Used

- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with Grid, Flexbox, and animations
- **JavaScript ES6+**: Async/await, DOM manipulation, and API integration
- **OpenWeatherMap API**: Weather data provider

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for API calls
- OpenWeatherMap API key (optional for demo)

### Installation

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **Search** for any city to see weather data

### API Setup (Optional)

To use live weather data:

1. **Sign up** at [OpenWeatherMap](https://openweathermap.org/api)
2. **Get your free API key**
3. **Replace** the `API_KEY` in the JavaScript code:
   ```javascript
   const API_KEY = 'your_actual_api_key_here';
   ```

## File Structure

```
weather-dashboard/
├── index.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # This file
└── demo/               # Demo screenshots (optional)
```

## Key Components

### HTML Structure
- **Header**: App title and description
- **Search**: City input field and search button
- **Current Weather**: Main weather display card
- **Forecast**: 5-day weather forecast grid
- **Loading/Error**: User feedback components

### CSS Features
- **Responsive Grid Layout**: Adapts to all screen sizes
- **Modern Design**: Glassmorphism effects and gradients
- **Smooth Animations**: Hover effects and transitions
- **Mobile-First**: Optimized for mobile devices

### JavaScript Functionality
- **API Integration**: Fetch weather data from OpenWeatherMap
- **Error Handling**: Fallback to demo data
- **DOM Manipulation**: Dynamic content updates
- **Event Handling**: Search functionality and keyboard support

## API Integration Details

### Current Weather Endpoint
```javascript
GET https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
```

### 5-Day Forecast Endpoint
```javascript
GET https://api.openweathermap.org/data/2.5/forecast?q={city}&appid={API_KEY}&units=metric
```

### Response Handling
- **Success**: Display real weather data
- **Error**: Show demo data with searched city name
- **Loading**: Visual feedback during API calls

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## Demo Data

When the API is unavailable, the app uses demo data featuring:
- London weather conditions
- 5-day forecast with varied weather patterns
- All UI components and interactions

## Customization

### Adding New Features
- **Geolocation**: Auto-detect user location
- **Units Toggle**: Switch between Celsius/Fahrenheit
- **Weather Maps**: Integrate weather radar
- **Favorites**: Save favorite cities

### Styling Modifications
- **Colors**: Update gradient and accent colors
- **Typography**: Change font families
- **Layout**: Modify grid structures
- **Animations**: Add more interactive effects

## Performance Optimization

- **Efficient API Calls**: Debounced search requests
- **Minimal DOM Updates**: Only update changed elements
- **CSS Optimization**: Hardware-accelerated animations
- **Image Optimization**: SVG icons for scalability

## Security Considerations

- **API Key**: Never expose in client-side code (use environment variables)
- **Input Validation**: Sanitize user input
- **HTTPS**: Always use secure connections
- **Rate Limiting**: Respect API usage limits

## Troubleshooting

### Common Issues

**Weather data not loading:**
- Check internet connection
- Verify API key is correct
- Ensure city name is spelled correctly

**Layout issues on mobile:**
- Clear browser cache
- Check viewport meta tag
- Verify CSS media queries

**API errors:**
- Check API key validity
- Verify API endpoint URLs
- Check for rate limiting

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- **OpenWeatherMap** for providing the weather API
- **Weather Icons** from various emoji sets
- **Design Inspiration** from modern weather apps

## Future Enhancements

- [ ] Weather alerts and notifications
- [ ] Historical weather data
- [ ] Multiple location support
- [ ] Weather-based recommendations
- [ ] Dark/light theme toggle
- [ ] Offline functionality with service workers

## Contact

For questions or support, please open an issue in the repository.

---

**Built with ❤️ for learning API integration and responsive web design**
