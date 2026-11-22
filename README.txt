# FireWatch — Fire Alarm Monitoring System (Academic Prototype)

## Run locally (no Java, Maven, or database required)
1. Extract this ZIP.
2. Open the `FireWatch_Fire_Alarm_Monitoring` folder.
3. Double-click `index.html` (or right-click -> Open with -> Chrome/Edge).
4. Sign in with one of the demo accounts below.

## Demo accounts
- Admin: `admin` / `FireWatch@123`
- Operator: `operator` / `Watch@123`

## Included modules
- Login screen and role demo
- Monitoring overview with status cards, chart and zone health
- Smoke, temperature and flame sensor cards with simulated readings
- Zone and device listing
- Alarm center with acknowledgement and response remarks
- Event history and filters
- Maintenance log
- CSV report exports
- Browser local storage for demo records

## Publish a public link (so others can open it)
This ZIP is a static website. To publish it:
1. Open Netlify Drop: firealarmmonitoring.netlify.app
2. Sign in or create a Netlify account.
3. Extract this ZIP on your computer.
4. Drag the extracted `FireWatch_Fire_Alarm_Monitoring` folder (the folder containing `index.html`) onto the Netlify Drop page.
5. Netlify will provide a public `https://....netlify.app` link. Share that link with anyone.

Alternative: upload the folder to a GitHub repository and enable GitHub Pages.

## Important limitations
This is a browser-based academic demonstration. Sensor values are simulated, records are stored in the current browser only, and the demo login is not production-grade authentication. It does not connect to physical smoke/heat/flame sensors, sirens, strobe lights, emergency services, cloud databases or real notification providers. It must never be used as a real building fire alarm or as a substitute for certified, professionally installed life-safety equipment. Real deployments require approved hardware, independent local alarm operation, secure backend/database, professional design, commissioning and regulatory compliance.
