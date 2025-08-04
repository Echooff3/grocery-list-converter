# Receipt to Shopping List Converter

A web application that converts grocery receipt images into organized, printable shopping lists using AI-powered item recognition and categorization.

## Features

- **Image Upload**: Upload photos of your grocery receipts
- **AI Processing**: Uses OpenRouter AI to parse and categorize items
- **Smart Grouping**: Automatically groups items by category (Produce, Dairy, etc.)
- **Impulse Purchase Detection**: Separates likely impulse buys into "Other" category
- **Printable Format**: Clean, organized shopping list ready for printing
- **Duplicate Removal**: Automatically removes duplicate items
- **Real-time Preview**: See your receipt image before processing

## How It Works

1. Enter your OpenRouter API key (get one free at [openrouter.ai](https://openrouter.ai))
2. Upload a photo of your grocery receipt
3. Click "Convert to Shopping List"
4. Receive an organized list grouped by category
5. Print or save your shopping list

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- OpenRouter API key (free tier available)
- JPEG/PNG receipt image

## Setup

1. Clone or download the repository
2. Open `index.html` in a web browser
3. Get your free API key from [openrouter.ai](https://openrouter.ai)
4. Upload a receipt image and convert!

## Supported AI Models

Currently uses `google/gemini-2.0-flash-lite-001` for optimal speed and accuracy. The app can be modified to use other OpenRouter models as needed.

## Privacy & Security

- All processing happens in your browser
- API keys are never stored or transmitted anywhere
- Receipt images are processed only with your chosen AI provider
- No data is collected or stored by the application

## Technical Details

### Frontend
- Pure HTML/CSS/JavaScript (no external dependencies)
- Responsive design works on mobile and desktop
- Real-time process logging for troubleshooting
- Client-side image processing

### AI Processing Flow
1. Image converted to base64
2. Sent to OpenRouter API with structured prompt
3. AI extracts and categorizes items
4. Response parsed and formatted into shopping list
5. Results displayed with print-friendly formatting

## Usage Tips

- Ensure receipt images are clear and well-lit
- Items should be legible in the photo
- The AI works best with standard grocery item names
- Check the "Other" category for potential impulse purchases

## Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## License

Give me credit where credit is due.
## Contributing

This is a single-file web app designed for simplicity. Feature requests and bug fixes welcome via pull requests.
