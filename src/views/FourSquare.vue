<script>
const MEETUP_CLIENT_ID = 'niqkagsfu07kb2coik832vljhm'; // this one is for local dev. http://127.0.0.1:3000
const MEETUP_REDIRECT_URI = `http://${window.location.href.split('/')[2]}/home`;

const url = `https://secure.meetup.com/oauth2/authorize?client_id=${MEETUP_CLIENT_ID}&response_type=token&redirect_uri=${MEETUP_REDIRECT_URI}`;
window.location.href = url;
</script>
