---
layout: splash
permalink: /leafbyte-faqs
title: LeafByte FAQs
classes:
  - leafbyte-faqs
header:
  overlay_color: "#85a266"
  overlay_image: images/Herbivory.jpg
excerpt: LeafByte is a free and open source mobile app for measuring herbivory quickly and accurately.
---

# Is LeafByte right for me?

##### How much does it cost?
LeafByte is free.

##### What devices does this app work on?
LeafByte is available on the [App Store](https://itunes.apple.com/us/app/leafbyte/id1362985339?mt=8) for Apple devices that run iOS (e.g. iPhones and iPads, but not MacBooks) with iOS version 9 and above. (The UX is optimized for iPhone 5 and later, but LeafByte also works on iPhone 3 and 4 and iPads.) As of June 2024, we are actively in the process of developing an Android version. If you would like to be emailed when the Android version is released [let us know](mailto:leafbyte@zoegp.science?subject=Interest%20in%20LeafByte%20on%20Android&body=Hello,%0AI'd%20like%20to%20express%20my%20interest%20in%20using%20an%20Android%20version%20of%20LeafByte.%20Please%20tell%20me%20when%20the%20app%20is%20available.%0A%0AThanks!).

##### Does this work for all different leaf shapes?
LeafByte works for a wide variety of leaf shapes, including both simple and compound leaves. You can even measure petals and flat flowers. However, it may be difficult to use for plants with needles or lacy leaves like those in the Apiaceae family.

##### Can I measure multiple leaves at once?
Unfortunately, LeafByte can only measure one leaf at a time. However, if two or more leaves are touching/overlapping, LeafByte will read them as a single leaf. If you don't mind pooling the data for multiple leaves, you can overlap them and analyze them as a single leaf. This will only give you a single number for leaf area and herbivory regardless of how many leaves you include, so you should only do this if you don't need separate data from each leaf.

##### How long does it take to measure each leaf?
The time to process a leaf depends on how much damage the leaf has and how simple the leaf image is. A simple leaf with no damage or only internal damage will take about 10-15 seconds to process. However, compound leaves or leaves with significant damage on the margin can take 30 seconds to two minutes to process. If you are doing bioassays in the lab, it can be faster to just take before and after measurements with the app and completely avoid drawing margins.

##### What barcodes are supported?
LeafByte can read standard linear and 2D barcodes. Supported linear barcodes are Code 128, Code 39, Code 39 mod 43, Code 93, EAN-8, EAN-13 (including UPC-A), Interleaved 2 of 5 (ITF), ITF-14, and UPC-E. Supported 2D barcodes are Aztec, Data Matrix, PDF417, and QR.

##### Can I use this for commercial plant monitoring?
Sure! LeafByte can be used for commercial plant health monitoring, academic research, home gardening, or any anything else you can imagine that requires measuring leaf area and herbivory. If you find LeafByte useful, we'd enjoy hearing about it!

##### Can I use it in the field/non-destructively?
Yes! We recommend a clipboard with a background sheet and [clear matte screen protector](https://www.amazon.com/gp/product/B07219ZSFT/ref=oh_aui_search_detailpage?ie=UTF8&psc=1) to hold the leaf flat.

##### Can this be used to measure disease?
LeafByte was not designed to measure diseases. If your disease creates distinct white spots on a dark leaf, or very dark spots on a light leaf, LeafByte should be able to measure it. However, if the disease creates spots without a distinct separation between the diseased and undiseased parts of the leaf, LeafByte will have a hard time distinguishing and will give imprecise readings.

##### What are the alternatives to LeafByte?
There are a number of other methods currently used for measuring leaf area and herbivory.

- The most widely used option, [ImageJ](https://imagej.nih.gov/ij/), is computer software developed by Wayne Rasband at the NIH. ImageJ is a broad, multipurpose image analysis app that is not optimized for this specific workflow. While it accurately measures leaf area and leaf area consumed, it is very slow to use. Processing each image takes 1-5 minutes with straightforward leaves, not including time spent uploading images into the program and saving the data in a useable format.
- The grid method, developed by [Coley (1983)](https://esajournals.onlinelibrary.wiley.com/doi/abs/10.2307/1942495), requires users to count leaf area and herbivory using a clear acetate sheet with a grid printed on it. Collecting data on both leaf size and herbivory often takes around 30 minutes per leaf, although just measuring herbivory can be done in a few seconds to a few minutes depending on the amount of leaf area that was consumed.
- Visual quantification, as described by [Marc Johnson et al. (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1111/een.12280), can quickly determine percent herbivory, but it requires training. The accuracy and precision of this method vary by leaf type and location of the herbivory. The accuracy of visual quantification for measuring absolute area is unstudied.
- [BioLeaf](http://bioleaf.icmc.usp.br/), a mobile app on Android, measures percent herbivory quickly and accurately, but cannot measure absolute area of either the leaf or the herbivory.
- [Leaf-IT](https://www.ncbi.nlm.nih.gov/pubmed/29188004), [Easy Leaf Area](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4103476/), and [Petiole](http://petioleapp.com/) are mobile apps designed to measure leaf area, but they are not currently able to measure herbivory.
- The [LI-COR LI-3100C Area Meter](https://www.licor.com/env/products/leaf_area/LI-3100C/) is a physical device to measure leaf area, but it's unable to measure herbivory and is very expensive (>$5,000).

Leafbyte improves on all of the above methods by quickly and accurately measuring leaf area, herbivory, and percent herbivory. It also records your data automatically in spreadsheets, reads barcodes, and records your location.


# Tips for Use

##### What do I need to use LeafByte?

You will need a white background with 4 black dots in a square or a dark background with 4 white dots in a square. You can print a background [here](LeafByte Scale Dots.pdf). We recommend a clipboard.

##### Do I really need to use a scale?

If you want absolute measures and correction for photos taken at an angle, yes. If you're careful to take photos straight on and only need percent measures, a scale is not necessary.

##### My leaves are not flat. What can I do?
We recommend using a matte screen protector or acetate sheet such as those found [here](https://www.amazon.com/gp/product/B07219ZSFT/ref=oh_aui_search_detailpage?ie=UTF8&psc=1) to keep the leaf flat.

##### Can I use LeafByte to measure the surface area of flowers, petals, or other leaf tissue?
Yes! If you are trying to measure light-colored leaf tissue such as white flower petals, you will need to use a black background with white dots and set *Use Black Background* in the settings.

##### What if most of the leaf was eaten?
LeafByte can’t tell where the leaf was after it's been eaten. It’s up to the user to draw in missing margins. If you are afraid most or all of the leaf will be eaten, we recommend taking before and after measurements and subtracting to get leaf area consumed. This is often faster than drawing missing leaf margins in the app.

##### My leaf has dentate margins, and I don't want to try redrawing all the spikes!
When drawing in missing margins on dentate leaves, you can just draw a straight line 1/3 of the way up your spikes (the math works out for that to be half the area of the spikes and half the area between the spikes). This trick will not work with lobed leaves or other non-trianguar margin shapes. 

##### What sizes of leaves can I use?
LeafByte can handle any leaves that you can photograph clearly. Some iOS devices can’t handle very tiny macro photography without a macro lense attachment. If you want to measure very large leaves like maize, consider a large white tarp with 4 dots in a square (which can be drawn on with a marker).

##### Why is saving sometimes slow?
There are two main reasons. 1) If you're saving to Google Drive and your internet is slow, saving will be slow. You can choose to save to the Files App on your phone to avoid using the internet. 2) Requesting phone GPS location can be slow in certain circumstances (including when you have poor signal), so if you're saving GPS info, you may experience (sometimes intermittent) slowness. Disable *Save GPS Location* in the settings to speed things up.

##### What does *Image may be fuzzy* mean?
This warning may be displayed on the Background Removal page if small adjustments to the slider would have significant effect on the image. This may indicate poor picture quality, perhaps due to low light, motion, or poor camera quality.

##### I saved data or images to my phone, but I don't have have iOS 11, so I don't have the Files App. How do I access my files?
See "How do I access my Files App data on my computer?" below.

##### How do I access my Files App data on my computer?
Plug your phone into a computer. On an older Mac, you can use iTunes to get files to your computer regardless of your iOS version. On a newer Mac, you can use Finder (full Finder interactions don't seem to work, so you may have to drag-and-drop the folder for your dataset to another folder on your computer in order to copy-paste off of the phone). On Windows, you should be able to achieve the same with File Explorer.

##### How do I change which Google account my data is being saved to?
In the settings, choose *Sign out of Google*, then re-select *Google Drive* as your save location. You'll be prompted to sign in again, and you can do so with your preferred account.

##### Why does LeafByte keep trying to scan barcodes when I just want to take a picture?
LeafByte has an optional setting to scan a barcode before each photo, useful for folks who mark each sample with a barcode. To disable, go to the settings and disable *Scan Barcodes*.

##### LeafByte is removing the exact wrong part of my image!
This is probably because LeafByte is set to use a black background and you have a white background (or vice versa). In the settings, toggle *Use Black Background*.

##### I need help getting a scale!
You can download a document with scales of different sizes [here](LeafByte Scale Dots.pdf), or make your own (just four dots in a square). Be sure to measure it before use, and enter the size in the settings. Size is measured from the center of one dot to another along one side of the square.

##### How do the calculations work? What's the computer science behind LeafByte?

- *Background Removal:* The background is removed by [thresholding](https://en.wikipedia.org/wiki/Thresholding_(image_processing)), where any pixels lighter than a cutoff level are removed. The cutoff level is automatically determined by [Otsu's method](https://en.wikipedia.org/wiki/Otsu%27s_method), which looks at a histogram of pixel brightnesses and finds the brightness level that most clearly separates the histogram into two distinct sections. The user can adjust this cutoff if needed.
- *Scale Identification:* The various objects in the image are found with [connected-components labeling](https://en.wikipedia.org/wiki/Connected-component_labeling), which identifies blobs of contiguous pixels. LeafByte assumes that the leaf is the largest object and the four dots of the scale are the next largest objects. The user can adjust the identification if needed.
- *Results:* Skew from the angle the photo was taken at is corrected for by using [planar homography](https://en.wikipedia.org/wiki/Homography_(computer_vision)) to adjust the image so that the scale marks make a square. Then [connected-components labeling](https://en.wikipedia.org/wiki/Connected-component_labeling) is used again to find the holes in the leaf, and pixels are counted.

You can read more details in our [publication](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13340) in *Methods in Ecology and Evolution*.

##### When I draw in the app, how does that affect the measurements?
Any areas enclosed by your drawings will be shaded in and counted as consumed leaf area (unless there's no path from the leaf to the enclosure; for example, a circle in open space). The lines you draw do not affect calculations in the places they overlap the leaf. In places where the drawn lines do not overlap the leaf, they will be counted as consumed area (unless there's no path from the leaf to the lines). In other words, drawing over an entire area is equivalent to just enclosing that area.

##### Why do you use 4 dots instead of a line or ruler for a scale?
Early iterations of LeafByte did use a single line as the scale. However, testing determined that photographing the leaf at even a seemingly reasonable angle could result in up to 40% distortion of the leaf’s absolute area. Having 4 dots in a square allows LeafByte to correct for most of the distortion from photographing at an angle. Now, taking the picture at even a 30 degree angle generally only leads to a 1-4% distortion of the leaf’s absolute area (due to the image capturing more shadow when at an angle).

##### I forgot to change the scale in the settings, so my data was analyzed with the wrong scale! Can I fix my data without reanalyzing each leaf?
Simply use the following equation to fix your data: correctData = wrongData * rightScale^2 / wrongScale^2.


# Contact and Logistics

##### I have an idea for how to improve the app! What should I do?
Send an email to [leafbyte@zoegp.science](mailto:leafbyte@zoegp.science). We are always excited to hear new ideas. However, we are thoughtful about each new feature in order to keep the app simple, and time constraints mean that we can’t always add new features immediately. Shoot us an email, and we will see what we can do.

##### I like this app, but I want to change it to fit my specific use case/idea/study system. Can I?
Yes! Please do. LeafByte is free and open source under the GPL-3.0 license. That said, you're welcome to [reach out to us](mailto:leafbyte@zoegp.science) in case the change would fit in LeafByte itself. If you do amend our app, we ask that you share the changes free and open source for the community to benefit from.

##### Where can I find the code?
On [GitHub](https://github.com/TheBeruriahIncident/leafbyte). We invite you to check out the code if you're interested. You can [reach out](mailto:leafbyte@zoegp.science) if you run into any issues.

##### I’m having problems with the app. What should I do?
Send an email to [leafbyte@zoegp.science](mailto:leafbyte@zoegp.science). If the problem is a bug, please include your iOS version, device model, and exactly what actions you were performing in the app when the bug happened. Without this information, we will have a hard time fixing the bug.

##### How has the app changed in different versions?
You can see your version number in the settings.

1.0.0 (Nov 6, 2018)
* Original release

1.1.0 (Jan 2, 2019)
* Scale length is now recorded in data sheets
* No more accidentally swiping back from the drawing page
* Leaf marker is now drawn at the top of the leaf to avoid covering anything
* Undo now uses less memory (relevant on iPhone 5 and before)

1.2.0 (June 19, 2019)
* Greater zoom is now supported (previously the maximum zoom was 10x; now it's 50x)
* Finding scale marks after user selection is now faster (helpful on older devices)
* Sufficiently large objects are ignored during manual scale selection, as they're unlikely to be the scale, and they take a long time to process on older devices

1.3.0 (Oct 9, 2019)
* When data is added to Google Sheets, numbers are properly recognized as numbers
* When Google Sheets are created, headers are frozen
* The "Back" button is now more accurately labeled "Save" on the Settings page

1.4.0 (Sept ???, 2024, the big 2024 refresh!) (Unreleased)
* The app code has been broadly refreshed and updated to ensure that everything is 2024-compliant and continues working given changes being made by both Apple and Google
* LeafByte no longer uses increasing amounts of memory the longer you use it, leading to crashes every few hundred images.
* The image selector is now more modern and allows search and zooming in and out of the image list.
* Google Sign-In specifically has been updated to get the minimal possible set of permissions to users' Google Drives (previously Google was granting several permissions LeafByte wasn't even asking for, so we've rewritten the whole login to avoid that) 
* Thresholding may be slightly faster now that it is rewritten to use the modern Metal language
* Text during barcode scanning (e.g. previews of what you scanned) is now easier to read
* Potential very brief unresponsiveness when initiating barcode scanning is removed
* FAQs and error reporting are more obvious on the home page
* The settings page is now sized correctly across different devices, and it now credits LeafByte collaborators
* LeafByte more precisely determines the center of oddly-shaped scale marks (it previously could be up to about a pixel off)
* In some rare situations that previously may have crashed, LeafByte no longer crashes: 
    * When linking to the LeafByte website on extremely slow internet
    * When the phone is particularly busy as a new screen finishes sliding out (extremely rare)
    * When you manage to return to the home screen while the app is already returning to the home screen (extremely rare)    
    * When the memory is affected in an odd way while the thresholding screen is prepared (extremely rare and perhaps theoretical)
* For several rare problematic cases, LeafByte now shows an error message rather than just crashing: 
    * When using LeafByte with camera access on a newer iOS version, then going to settings and removing camera access, then trying to take a picture in LeafByte 
    * When saving a corrupt image that cannot be converted into a png (this appears once in a crash report without clear cause)
    * When failing to save a file to the Files App (this appears once in a crash report without clear cause; perhaps the disk was full?)
    * When the image chosen in the image picker cannot be loaded (this appears once in a crash report without clear cause)
    * When iOS itself cannot process your chosen image (this appears once in a crash report without clear cause)
    * When saving data to Google Drive crashes due to malformed data from Google (this is maybe just theoretical)
    * When the barcode scanner is used on a device with no camera (this is maybe just theoretical)
* Various typos are fixed

##### How do I cite this in my paper?
Our methods paper is available [here](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13340) and may be cited with the citation below.

Getman‐Pickering, Z. L., Campbell, A., Aflitto, N., Grele, A., Davis, J. K., & Ugine, T. A. (2020). LeafByte: A mobile application that measures leaf area and herbivory quickly and accurately. Methods in Ecology and Evolution, 2041–210X.13340. doi:10.1111/2041-210X.13340

##### What data do you collect? What is LeafByte's privacy policy?
LeafByte itself gathers no data. We do not see or collect any information from or about your Google account. We do not see the pictures you take or the data you measure. (you can [see all the code in LeafByte](https://github.com/TheBeruriahIncident/leafbyte) if you want)

Apple (not us) does gather some info about all apps in the App Store, such as usage info (e.g. how often is the app downloaded, does it get used) and crash reports (e.g. how many times did the app crash, what line of code did it crash on). We will likely be checking the crash reports to ensure LeafByte is not buggy and to fix bugs if they do occur. Note that these crash reports just tell us the line in our code; they don't tell us what you were doing or what data was involved.

##### What access does LeafByte have to my Google Drive? Is it requesting too much access?
LeafByte has no access to your Google Drive unless you choose to save to Google Drive and explicitly give LeafByte access. Even then, LeafByte requests the minimum access it needs.

Specifically, LeafByte requests two permissions: the ability to get your Google user id (which is a large number that identifies you) and the ability to write to LeafByte's files in Google Drive. Note that LeafByte does not receive any access to files that it didn't create. On a [technical level](https://developers.google.com/identity/protocols/oauth2/scopes), LeafByte requests the `openid` and `https://www.googleapis.com/auth/drive.file` OAuth 2.0 scopes.

LeafByte needs the Google user id so that it works smoothly if multiple Google accounts are used with it. Note that this Google user id never leaves your device: it is only used internally to avoid errors.

LeafByte of course needs Google Drive access to save to Google Drive. This allows LeafByte to create new folders, put images in those folders, create datasheets, and append rows to those datasheets. We never view/access or edit previous images or data. 

All that said, the Google sign-in will show these two pages:

<p float="left">
  <img src="images/Login page 1.jpg" width="300" alt="The first page of Google sign-in" style="margin-left: 50px"/>
  <img src="images/Login page 2.jpg" width="300" alt="The second page of Google sign-in" style="margin-left: 50px"/> 
</p>

Access to your Google user id is represented as "Associate you with your personal info on Google". We do not ever use the Google user id to access any personal info. The first page says "Google will share your name, email address, language preference, and profile picture with LeafByte." This is misleading, as Google never sends any of that info to us. It may be possible that we'd be able to use the user id to request that info, but [Google's docs](https://developers.google.com/identity/protocols/oauth2/scopes) suggest that we (appropriately) wouldn't even have access to that. 

It's worth noting that at some point between the initial release of LeafByte and the preparation for releasing 1.4.0, Google started automatically giving extra access to apps, without apps themselves even asking for it, since Google assumed everyone would want that access. It looked like this:

<img src="images/Old login page.jpg" width="300" alt="The old, bad Google sign-in" float="left" style="margin-left: 50px" />

We never used any of that additional access, and once we found out this was happening, we rewrote our login to avoid being granted any extra access.

You can always explicitly revoke any access you've given to LeafByte. Here are [Google's instructions to do so](https://support.google.com/accounts/answer/13533235?hl=en).

To reiterate, LeafByte itself gathers no data. We do not see or collect any information from or about your Google account. We do not see the pictures you take or the data you measure. You can [see all the code in LeafByte](https://github.com/TheBeruriahIncident/leafbyte) and validate all of this.

##### Who's talking about LeafByte?
* [**Cornell Chronicle**: LeafByte app measures damage from chomping insects](https://news.cornell.edu/stories/2019/03/leafbyte-app-measures-damage-chomping-insects)
* [**The Entomological Society of America's Entomology Today**: How a Team of Grad Students Built a Mobile App for Entomologists](https://entomologytoday.org/2019/08/19/how-team-grad-students-built-mobile-app-entomologists-leafbyte/)
* [**Discussions on Twitter**](https://twitter.com/search?q=leafbyte&src=typed_query&f=top)

##### Who made this?
LeafByte was made by Zoe & Abigail Getman-Pickering. Zoe is a scientist interested in plant-insect interactions, with a PhD from Cornell's Department of Entomology. Abigail is a software engineer and has worked at various prominent software companies. Nick Aflitto, Ari Grele, George Stack, Todd Ugine, Jules Davis, Heather Grab, Jose Rangel, Sheyla Finkner, Sheyla Lugay, Fiona MacNeil, and Abby Dittmar all worked on testing the app and contributed ideas for features and improvements. Eric Raboin helped with the projective geometry equations. Nick Aflitto and Julia Miller took photos for the website and tutorial respectively.
