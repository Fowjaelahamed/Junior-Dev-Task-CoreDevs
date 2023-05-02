# Junior-Dev-Task-CoreDevs
**Junior Dev Bug(Project Packer):**

 - [ ]  In Checkout components, checkout is not defined as default function. So it showed error.
**Solution**: I just make checkout as default function so we can import as it is.

 - [ ] There was some warnings from Eslint when using useEffect in Order.jsx, CheckoutPage.jsx components.
**Solution**: I just had to comment using this “// eslint-disable-next-line react-hooks/exhaustive-deps”

 - [ ] There was some bugs when using key in Order components.
**Solution**: we shouldn't use key as prop and that is why we are getting this bug. And i just create a new prop with new name(mykey) and pass key value with this.
![enter image description here](https://drive.google.com/file/d/1hO1JkDPt_mv9tS6NYV9rO_7p9b22d04T/view?usp=share_link)
**Junior Dev Back Bug:**

 - [ ] When running backend code it shows that it expected connection string start with mongodb://.
**Solution**: I just add mongodbURL in settings.json and when i run backend code it works fine without any error.
![Backend Running](https://drive.google.com/file/d/1TbykqWqa6DbkTJRY8xFOqJ-93cud4_kI/view?usp=share_link)
 

