# Grant's Lesser-PageCrypt

This is a fork of https://github.com/Greenheart/pagecrypt with the following
tweaks:

- Less secure
  - Does not remove the password from the fragment of the URL
  - Saves the password in storage instead of the derived key
  - Uses localStorage instead of sessionStorage to save the password
- `deno` CLI only

I essentially modified this to serve my particular use case and nothing else.

Feel free to use at your own risk. If you want something different, feel free to
fork this repo and modify it to your liking (just be sure to keep the license).
I likely won't accept issues or pull requests.
