# House Marketplace

Find and list houses for sale or for rent. This is a React / Firebase v9 .

## Usage

### Geolocation

The listings use Google geocoding to get the coords from the address field. You need to either rename .env.example to .env and add your Google Geocode API key OR in the **CreateListing.jsx** file you can set **geolocationEnabled** to "false" and it will add a lat/lng field to the form.

### Run

```bash
npm start
```
<img width="955" alt="image" src="https://user-images.githubusercontent.com/48060488/223770635-c622c82a-a3ce-46b8-aebc-87fa0184d434.png">
<img width="946" alt="image" src="https://user-images.githubusercontent.com/48060488/223770725-cab0d8ce-39e1-4baf-aad9-b83c7f798c54.png">
<img width="959" alt="image" src="https://user-images.githubusercontent.com/48060488/223770790-5c2370cf-a5b7-4b53-a33d-afb51a8f5344.png">

