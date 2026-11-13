# Divine Earth Holidays — Admin Panel Guide

## Open the admin panel
- Website: open `index.html`.
- Admin: open `admin.html` or click the user/admin icon in the website header (before **Book Now**).
- Email: `divineearthholiday@gmail.com`
- Password: `divineearth5612`

## Admin sections
- **Packages:** edit title, selling/old price, category, duration, days, nights, destination, per-person rate, rating, badge, short description, highlights, inclusions, exclusions, hotel/stay information, itinerary, custom-package note, detail-page link and package image. Add, duplicate, hide or restore packages.
- **Media Library:** browse all 99 bundled website images, upload multiple images, search the library and delete uploaded images. From a package or hero slide, choose **Choose Image** to select any library image.
- **Hero Slider:** add/remove slides and choose images from the Media Library.
- **Website Settings / Page Content:** edit common brand and text settings.

## How to change a package image
1. Open Admin → Packages.
2. Expand the package you want to edit.
3. Click **Choose Image** to select an existing image, or upload a new image using the file control beside the preview.
4. Update the package fields and click **Save All Package Changes**.

## Important deployment limitation
This is a static HTML version. Text/settings are stored in this browser's local storage and uploaded image files are stored in this browser's IndexedDB. Updates therefore appear on the same browser/device and website origin only. They do not update the deployed HTML files or synchronize to other visitors/devices. A public production admin panel needs server-side authentication and a shared database/file-storage service (such as Firebase or Supabase). Do not treat the front-end password as secure server authentication.
