# Malaysia Prayer Times Viewer (Waktu Solat)

A user-friendly front-end application to check daily prayer times in Malaysia based on official JAKIM zones. This web page allows users to easily select their specific zone and view the prayer schedule for the current day.

## Features

* Displays all primary prayer times: Fajr, Syuruk (Sunrise), Dhuhr, Asr, Maghrib, and Isha.
* Comprehensive JAKIM zone selection via a dropdown menu, populated with codes, states (negeri), and districts (daerah).
* Shows the current Gregorian and Hijri dates corresponding to the prayer times.
* Responsive design for usability on different devices.
* Dynamic fetching of data with loading indicators and error messages.

## Technologies Used

* **API:** `api.waktusolat.app` for sourcing prayer time data.
* **Frontend Core:** HTML, JavaScript (ES6+)
* **Styling:** **Tailwind CSS** (via CDN for rapid and responsive UI development)
* **JavaScript Library:** **jQuery** (for DOM manipulation and simplified AJAX requests)
* **Gemini 2.5 Pro (Preview Version)

## API Used

This application build by the Gemini Pro 2.5 (Preview) version, I on ly do the prompting. This application also relies on the public API provided by **[api.waktusolat.app](https://api.waktusolat.app/)**. Please refer to their documentation for more information about the API itself and its usage terms.

## How to Run Locally

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/YYasirIrsyad/malaysia-prayer-times.git](https://github.com/YasirIrsyad/malaysia-prayer-times.git)
    cd malaysia-prayer-time
    ```

2.  **Open `index.html` in your browser:**
    Navigate to the project folder and open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).

No special build steps or local server (for this version) are required as it's a client-side application using CDN links for Tailwind CSS and jQuery.
