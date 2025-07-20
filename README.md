
Live project view : https://gnaneswariganisetti.github.io/japan_route_visualizer/

# Japanese Rail Route Visualizer

<img width="877" height="800" alt="image" src="https://github.com/user-attachments/assets/a4096524-2348-47e5-a28e-f7c1af84f7f6" />


## Overview

A web-based visualization tool that animates train routes between Tokyo stations in the style of Japanese rail systems. This interactive application displays routes with accurate line colors, station stops, and estimated arrival times, complete with a moving train animation.

## Features

- **Interactive Route Selection**: Choose from multiple Tokyo stations and route options
- **Authentic Visuals**: 
  - Color-coded rail lines matching real Tokyo train lines
  - Japanese/English bilingual interface
  - Japan-themed design elements
- **Animated Train**: Smooth SVG animation along the selected route
- **Route Information**:
  - ETA calculation
  - Line information
  - Duration and station count
  - Detailed station list with timing

## Technologies Used

- HTML5
- CSS3 (with animations)
- JavaScript (ES6)
- SVG for route visualization

## Installation

No installation required! This is a client-side web application that runs directly in the browser.

To use locally:
1. Clone this repository or download the files
2. Open `index.html` in any modern web browser

## Usage

1. Select a starting station from the "出発駅 (From)" dropdown
2. Select a destination station from the "到着駅 (To)" dropdown
3. Choose a route option:
   - 最速 (Fastest) - The quickest route
   - 山手線 (Yamanote Line) - Uses the Yamanote loop line
   - 乗換少 (Least Transfer) - Minimizes transfers
4. Click "検索 (Search)" to visualize the route
5. Watch the animation and view route details

## Supported Routes

The application currently supports routes between these major Tokyo stations:
- 東京 (Tokyo)
- 新宿 (Shinjuku)
- 渋谷 (Shibuya)
- 池袋 (Ikebukuro)
- 秋葉原 (Akihabara)
- 上野 (Ueno)
- 品川 (Shinagawa)

## Customization

To add more stations or routes:
1. Edit the `stations` object in the JavaScript to add new stations with coordinates
2. Add new route definitions to the `routes` object
3. Define new predefined routes in the `predefinedRoutes` object

## Future Enhancements

- Add more Tokyo stations and lines
- Implement transfer points between lines
- Add realistic station announcements
- Improve mobile responsiveness
- Add departure board functionality

## License

This project is open source and available under the MIT License.

## Credits

Created as a demonstration of SVG animations and Japanese rail visualization. Station coordinates and route times are approximations for demonstration purposes.
