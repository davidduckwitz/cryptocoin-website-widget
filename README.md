# cryptocoin-website-widget
Show Balance and QR code of bitcoin / Litecoin / Dogecoin and more...

Cryptocoin-Website-Widget


Another _Bitcoin_, _Litecoin_ and _Dogecoin_ Donation Button

Released under the Open Source MIT License (see LICENSE file for details).
Installation

A. Grab the latest version from GitHub: _https://github.com/davidduckwitz/cryptocoin-website-widget_

B. Open coin.js and find:

source: 'http://widget.bitcoin-tech.com/'

C. Change the URL portion of this line to your own server/path.

D. (optional) Open lookup.php and consider implementing a caching method based on your own style and preference.
`Example Code`

<script src="coin.js"></script>
	<script>
	CoinWidgetCom.go({
		/* make sure you update the wallet_address or you will not get your donations */
		wallet_address: "LY1L6M6yG26b4sRkLv4BbkmHhPn8GR5fFm"
		, currency: "bitcoin"
		, counter: "count"
		, alignment: "bl"
		, qrcode: true
		, auto_show: false
		, lbl_button: "Donate"
		, lbl_address: "Donate Bitcoins to this Address:"
		, lbl_count: "donations"
		, lbl_amount: "BTC"
		, amount: "show"
 		, milli: true
	});
	</script>
