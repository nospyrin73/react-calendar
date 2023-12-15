# Customized React Calendar

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![React Version](https://img.shields.io/badge/React-%5E16.0.0-%2361DAFB)](https://reactjs.org/)
[![npm Version](https://img.shields.io/badge/npm-%5E7.0.0-%23CB3837)](https://www.npmjs.com/)

<div align="center">
  <img width="436" height="398" src="https://projects.wojtekmaj.pl/react-calendar/react-calendar.jpg">
</div>

This is a customized fork of the popular `react-calendar` library with several additional features for enhanced flexibility and customization. Created for use in [Novatours](https://novaturas.lt/) project

### Added Features:

1. **Scrollable Calendar:**
   - The calendar is now scrollable, allowing users to navigate through months by scrolling horizontally.

2. **Month Label Localization:**
   - Standard month labels are now localized for better internationalization support.

3. **Sticky-able Weekday Names:**
   - Weekday names are now sticky, providing a consistent reference as users scroll through the calendar.

4. **Display Days from Neighboring Month in the Last Row:**
   - Only displays days from the neighboring month in the last row if there are more than one day from the current month.

5. **Variable Number of Months:**
   - Introduces the option to display a variable number of months, providing flexibility in calendar layout.

## Installation

To install this customized React Calendar, you can use npm:

```bash
npm install nova-react-calendar
```

## Usage

Import the customized calendar component in your React application:

```javascript
import Calendar from 'customized-react-calendar';

// Use Calendar in your component
```

### Props

- `scrollable` (boolean, default: `true`): Enable or disable the scrollable feature.
- `locale` (string, default: `'en-US'`): Set the desired locale for month labels.
- `stickyWeekdays` (boolean, default: `true`): Enable or disable sticky weekday names.
- `displayNeighborDays` (boolean, default: `true`): Control the display of days from the neighboring month in the last row.
- `numberOfMonths` (number, default: `1`): Set the number of months to display.

## Example

```jsx
import React from 'react';
import Calendar from 'nova-react-calendar';

const MyCustomCalendar = () => {
  return <CustomizedCalendar />;
};

export default MyCustomCalendar;
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This customized React Calendar is built upon the foundation of of a fork of the original `react-calendar` => [iui-react-calendar](https://github.com/chahatbahl/react-calendar/).

Feel free to contribute and open issues if you encounter any problems or have suggestions for improvements.

Happy coding!

---
