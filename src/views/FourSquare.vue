<script>
const FOURSQUARE_CLIENT_ID = 'SOTVCGCEZKOO3WRVWQ0Q4TWAFT2JCHFO4CAAATWEVXPS2HTY'; // this one is for local dev. http://127.0.0.1:3000
const FOURSQUARE_REDIRECT_URI = `http://${
  window.location.href.split('/')[2]
}/home`;

const url = `https://foursquare.com/oauth2/authenticate?client_id=${FOURSQUARE_CLIENT_ID}&response_type=token&redirect_uri=${FOURSQUARE_REDIRECT_URI}`;
window.location.href = url;
</script>
