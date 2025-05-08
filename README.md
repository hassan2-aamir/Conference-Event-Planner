# Conference Event Planner

A comprehensive React application that helps users plan and budget for conference events by selecting venues, add-ons, and meal options with real-time cost calculation.

## Features

- **Venue Selection**: Choose from multiple venue options with different capacities
- **Add-ons Management**: Select necessary equipment like projectors, speakers, and microphones
- **Meal Planning**: Plan meals for attendees with options for breakfast, lunch, dinner, and high tea
- **Real-time Cost Calculation**: Instantly see the total cost as selections are made
- **Detailed Cost Breakdown**: View itemized cost details for better budget management

## Technology Stack

- React
- Redux Toolkit for state management
- CSS for styling
- Vite as the build tool

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/hassan2-aamir/Conference-Event-Planner.git
cd Conference-Event-Planner/conference_event_planner
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
# or
yarn build
```

## Usage

1. Click the "Get Started" button on the landing page
2. Navigate through the available sections:
    - **Venue**: Select the appropriate room(s) based on your needs
    - **Add-ons**: Choose necessary equipment for your event
    - **Meals**: Plan meals for your attendees
3. Use the "Show Details" button to view the complete cost breakdown

## Project Structure

- `src/` - Contains all the source code
  - `components/` - React components
  - `store.js` - Redux store configuration
  - `*Slice.js` - Redux slices for state management
  - `*.css` - Styling files

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request