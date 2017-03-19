# Verues
Please note: Verues is not 100% functional in its current state. It is not ready for public use. If you would like to help the site, feel free to contribute. The contents of this Read Me may or may not be implemented yet in the final product.

Verues will be a free website that allows creators to publicize their work. It will allow users to embed their videos in a template, and add a link to that on the home page. They will add their link to the top, so when you upload your work, users will see it.
It will be completly open sourced, so anyone can improve the site as time goes on.

# Adding a video to Verues:

If you would like to add a video to Verues, please ensure:
- You own the worldwide rights to your work, you have written permission to reupload the work, or it's in the public domain.
- It is a generic piece of entertainment. You must upload a piece of work that everyone will enjoy. The viewer shouldn't need to know who uploaded the video in order to understand. In most cases, your video should be a live-action film or cartoon.
- It makes sense. A lot of shows today, mainly those aimed at kids, are just flat out stupid and make no sense according to numerous people. If you are uploading something, make sure it is something people will like.
- Rate your video for the correct age group. If it is something for kids, suggest the age group for 3-10. If it is full of violence and colorful words, perhaps set the age group to 18+. If it is in the middle, perhaps set the age group to 11-17.

To upload your video, navigate to the `subpages` directory, and you should see `template.html`. If you have the repository cloned to your desktop (which is recommended), copy the template to the `/subpages/Videos/` directory and rename it to the title of your video (your show) without spaces or punctuation, followed by the number of the season than episode. For example, if you have a show called Danny's Adventure, you would call the template `DannysAdventure12`, which would mean this is Episode 2 in the first season of Danny's Adventure.
If you have your your show's media on YouTube, you can embed it in the template. If not, upload it to the `/media/media/` directory, and set the width to `1280` and the height to `720` (1280x720). Your tag should look like this:
`<video width="1280" height="720" controls>
  <source src="/media/media/DannysAdventure12" type="video/mp4">
Your browser does not support the video tag.
</video>`
Put this in place of `[Replace this text, with the brackets, with the embedded code to your video.]`.
