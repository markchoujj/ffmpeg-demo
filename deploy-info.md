# Deployment Guide

## Files to Deploy
Deploy the entire directory containing:
- index-comparison.html (main grid view)
- details.html (details page)
- 22-slow/ (video folder)
- 26-fast/ (video folder)
- thumbnails/ (thumbnail images)

## Recommended: Netlify Drop

1. Visit: https://app.netlify.com/drop
2. Drag this entire folder onto the page
3. Wait for upload (may take a few minutes due to video files)
4. Get your shareable URL instantly!

## Total Size Check
Run this command to see your total folder size:
du -sh .

## Netlify Limits (Free Tier)
- Bandwidth: 100GB/month
- Build minutes: 300/month
- Sites: Unlimited
- File size: No hard limit for static files

## Custom Domain (Optional)
After deploying, you can:
- Change the random URL to a custom subdomain (e.g., video-demo.netlify.app)
- Add your own domain if you have one

## Tips for Sharing
- The URL will work immediately
- Videos load on-demand (lazy loading)
- Share the index-comparison.html as the main entry point
