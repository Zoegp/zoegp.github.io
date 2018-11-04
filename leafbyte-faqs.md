---
layout: splash
permalink: /leafbyte-faqs
title: LeafByte FAQs
header:
  overlay_color: "#85a266"
  overlay_image: images/Herbivory.jpg
---

# Is LeafByte right for me?

##### How much does it cost?
LeafByte is free.

##### What devices does this app work on?
LeafByte is available on the [App Store](https://www.apple.com/ios/app-store/) for Apple devices that run iOS 9 and above. (The UX is optimized for iPhone 5 and later, but LeafByte also works on iPhone 3 and 4 and iPads.) Development of an Android version is being prioritized based on interest, so please [let us know](mailto:leafbyte@zoegp.science?subject=Interest%20in%20LeafByte%20on%20Android&body=Hello,%0AI'd%20like%20to%20express%20my%20interest%20in%20using%20an%20Android%20version%20of%20LeafByte.%0A%0AThanks!) if you need an Android version.

##### Does this work for all different leaf shapes?
LeafByte works for a wide variety of leaf shapes, including both simple and compound leaves. You can even measure petals and flat flowers. However, it may be difficult to use for plants with needles or lacy leaves like those in the Apiaceae family.

##### How long does it take to measure each leaf?
The time to process a leaf depends on how much damage the leaf has and how simple the leaf image is. A simple leaf with no damage, or only internal damage will take about 10-15 seconds to process. However, compound leaves or leaves with significant damage on the margin can take 30 seconds to two minutes to process. If you are doing bioassays in the lab, it can be faster to just take before and after measurements with the app and completely avoid drawing margins.

##### What barcodes are supported?
LeafByte can read standard linear and 2D barcodes. Supported linear barcodes are Code 128, Code 39, Code 39 mod 43, Code 93, EAN-8, EAN-13 (including UPC-A), Interleaved 2 of 5 (ITF), ITF-14, and UPC-E. Supported 2D barcodes are Aztec, Data Matrix, PDF417, and QR.

##### Can I use this for commercial plant monitoring?
Sure! LeafByte can be used for comperical plant health monitoring, academic research, home gardening, or any anything else you can imagine that requires measuring leaf area and herbivory. If you find LeafByte useful, we'd enjoy hearing!

##### Can I use it in the field/non-destructively?
Yes! We recommend a clipboard with a background sheet and [clear matte screen protector](https://www.amazon.com/gp/product/B07219ZSFT/ref=oh_aui_search_detailpage?ie=UTF8&psc=1) to hold the leaf flat.

##### Can this be used to measure disease?
LeafByte was not designed to measure diseases. If your disease creates distinct white spots on a dark leaf, or very dark spots on a light leaf, LeafByte should be able to measure it. However, if the disease creates spots without a distinct separation between the diseased and un-diseased part of the leaf, LeafByte will have a hard time distinguishing and will give imprecise readings.

##### What are the alternatives to LeafByte?
There are a number of different methods currently used for measuring leaf area and herbivory.

- The most widely used option, [ImageJ](https://imagej.nih.gov/ij/), is computer software developed by Wayne Rasband at the NIH. ImageJ is a broad, multipurpose image analysis app that is not optimized for this specific workflow. While it accurately measures leaf area and leaf area consumed, it is very slow to use. Processing each image takes 1-5 minutes with straightforward leaves, not including time spent uploading images into the program, and saving the data in a useable format.
- The Grid Method, developed by [Coley (1983)](https://esajournals.onlinelibrary.wiley.com/doi/abs/10.2307/1942495), requires users to count leaf area and herbivory using a clear acetate sheet with a grid printed on it. Collecting data on both leaf size and herbivory often takes around 30 minutes per leaf, although just measuring herbivory can be done in a few seconds to a few minutes depending on the amount of leaf area that was consumed.
- Visual quantification, as described by [Marc Johnson et al. (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1111/een.12280), can quickly determine percent herbivory, but requires training. The accuracy and precision of this method vary by leaf type and location of the herbivory. The accuracy of visual quantification for measuring absolute area is unstudied.
- [BioLeaf](http://bioleaf.icmc.usp.br/), a mobile app on Android, measures percent herbivory quickly and accurately, but cannot measure absolute area of either the leaf or the herbivory.</li>
- [Leaf-IT](https://www.ncbi.nlm.nih.gov/pubmed/29188004), [Easy Leaf Area](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4103476/), and [Petiole](http://petioleapp.com/) are mobile apps designed to measure leaf area, but they are not currently able to measure herbivory.
- [LI-COR LI-3100C Area Meter](https://www.licor.com/env/products/leaf_area/LI-3100C/) is a physical device to measure leaf area, but it's unable to measure herbivory and is very expensive (>$5,000).

Leafbyte improves on all of the above methods by quickly and accurately measuring leaf area, herbivory, and percent herbivory. It also records your data automatically in spreadsheets, reads barcodes, and records your location.

# Tips for Use

##### What do I need to use LeafByte?

You will need a white background with 4 black dots in a square or a dark background with 4 white dots in a square. You can print a background [here](assets/LeafByte%20Scale%20Dots.pdf). We recommend a clipboard.

##### My leaves are not flat. What can I do?
We recommend using a matte screen protector or acetate sheet such as those found [here](https://www.amazon.com/gp/product/B07219ZSFT/ref=oh_aui_search_detailpage?ie=UTF8&psc=1) to keep the leaf flat.

##### Can I use LeafByte to measure the surface area of flowers, petals, or other leaf tissue?
Yes! If you are trying to measure light-colored leaf tissue such as white flower petals, you will need to use a black background with white dots and set *Use Black Background* in the Settings.

##### What if most of the leaf was eaten?
LeafByte can’t tell where the leaf was after it's been eaten. It’s up to the user to draw in missing margins. If you are afraid most or all of the leaf will be eaten, we recommend taking before and after measurements and subtracting values to get leaf area consumed. This is often faster than drawing missing leaf margins in the app.

##### What sizes of leaves can I use?
LeafByte can handle any leaves that you can photograph clearly. Some iOS devices can’t handle very tiny macro photography without a macro lense attachment. If you want to measure very large leaves like maize, consider a large white tarp with 4 dots in a square (which can be drawn on with a marker).

##### Why is saving sometimes slow?
There are two main reasons. 1) If you're saving to Google Drive and your internet is slow, saving will be slow. You can choose to save to the Files App on your phone to avoid using the internet. 2) Requesting phone GPS location can be slow in certain circumstances, so if you're saving GPS info, you may experience (sometimes intermittent) slowness. Disable *Save GPS Location* in Settings to speed things up.

##### What does *Image may be fuzzy* mean?
This warning may be displayed on the background removal page if small adjustments to the slider would have significant effect on the image. This may indicate poor picture quality, perhaps due to low light, motion, or poor camera quality.

##### I saved data or images to my phone, but I don't have have iOS 11, so I don't have the Files App. How do I get at my files?
You can use iTunes to get files to your computer regardless of your iOS version.

##### How do I change which Google account my data is being saved to?
In the Settings, choose *Sign out of Google*, then re-select *Google Drive* as your save location. You'll be prompted to sign in again, and you can do so with your preferred account.

##### Why does LeafByte keep trying to scan barcodes when I just want to take a picture?
LeafByte has an optional setting to scan a barcode before each photo, useful for folks who mark each sample with a barcode. To disable, go to the Settings and disable *Scan Barcodes*.

##### LeafByte is removing the exact wrong part of my image!
This is probably because LeafByte is set to use a black background and you have a white background (or vice versa). In the Settings, toggle *Use Black Background*.

##### I need help making a scale!
You can download a document with scales of different sizes [here](assets/LeafByte%20Scale%20Dots.pdf), or make your own (make four dots in a square). Just be sure to measure it before use, and enter the size in the Settings. Size is measured from the center of one dot to another along one side of the square.

##### How do the calculations work? What's the computer science behind LeafByte?

- *Background Removal:* The background is removed by [thresholding](https://en.wikipedia.org/wiki/Thresholding_(image_processing)), where any pixels lighter than a cutoff level are removed. The cutoff level is automatically determined by [Otsu's method](https://en.wikipedia.org/wiki/Otsu%27s_method), which looks at a histogram of pixel brightnesses and finds the brightness level that most clearly separates the histogram into two distinct sections. The user can adjust this cutoff if needed.
- *Scale Identification:* The various objects in the image are found with [connected-components labeling](https://en.wikipedia.org/wiki/Connected-component_labeling), which identifies blobs of contiguous pixels. LeafByte assumes that the leaf is the largest object and the four dots of the scale are the next largest objects. The user can adjust the identification if needed.
- *Results:* Any skew from the angle the photo was taken at is corrected for by using [planar homography](https://en.wikipedia.org/wiki/Homography_(computer_vision)) to adjust the image so that the scale marks make a square. Then [connected-components labeling](https://en.wikipedia.org/wiki/Connected-component_labeling) is used again to find the holes in the leaf and pixels are counted.

##### When I draw in the app, how does that affect the measurements?
Any areas enclosed by your drawings will be shaded in and counted as consumed leaf area (unless there's no path from the leaf to the enclosure; for example, a circle in open space). The lines you draw do not affect calculations in the places they overlap the leaf. In places where the drawn lines do not overlap the leaf, they will be counted as consumed area (unless there's no path from the leaf to the lines). In other words, drawing over an entire area is equivalent to just enclosing that area.

##### Why do you use 4 dots instead of a line for a scale?
Early iterations of LeafByte did use a single line as the scale. However, testing determined that photographing the leaf at even a seemgly reasonable angle could result in up to 40% distortion of the leaf’s absolute area. Having 4 dots in a square allows LeafByte to correct for most of the distortion from photographing at an angle. Now, taking the picture at even a 30 degree angle generally only leads to a 1-4% distortion of the leaf’s absolute area (due to seeing more shadow when at an angle).

# Contact and Logistics

##### I have an idea for how to improve the app! What should I do?
Send an email to [leafbyte@zoegp.science](mailto:leafbyte@zoegp.science). We are always excited to hear new ideas. However, we are thoughtful about each new feature in order to keep the app simple, and time constraints mean that we can’t always add new features immediately. Shoot us an email, and we will see what we can do.

##### I like this app, but I want to change it to fit my specific use case/idea/study system. Can I?
Yes! Please do. LeafByte is free and open source under the GPL-3.0 license. If you amend our app, we ask that you share the changes free and open source for the community to benefit from.

##### Where can I find the code?
On [GitHub](https://github.com/akroy/leafbyte). Pull requests are welcome!

##### I’m having problems with the app. What should I do?
Send an email to [leafbyte@zoegp.science](mailto:leafbyte@zoegp.science). If the problem is a bug, please include your iOS version, device model, and exactly what actions you were performing in the app when the bug happened. Without this information, we will have a hard time fixing the bug.

##### How do I cite this in my paper?
A manuscript is currently in prep; check back here for more information. The software can be temporarily be referenced as follows:
Campbell, A. and Getman-Pickering, Z. (2018). LeafByte [iOS application]. Ithaca, NY. zoegp.science/leafbyte

##### What data do you collect? What is LeafByte's privacy policy?
LeafByte itself gathers no data. We do not see or collect any information from or about your Google account. We do not see the pictures you take or the data you measure. (you can [see all the code in LeafByte](https://github.com/akroy/leafbyte) if you want)

Apple (not us) does gather some info about all apps in the App Store, such as usage info (e.g. how often is the app downloaded, does it get used) and crash reports (e.g. how many times did the app crash, what line of code did it crash on). We will likely be checking the crash reports to ensure LeafByte is not buggy and to fix bugs if they do occur. Note that these crash reports just tell us the line in our code; they don't tell us what you were doing or what data was involved.

##### Who made this?
LeafByte was made by Zoe Getman-Pickering and Adam Campbell. Zoe is a PhD candidate in Cornell University's Department of Entomology. Adam is a software engineer at Palantir. Nick Aflitto, Ari Greele, and Todd Ugine all contributed ideas for improvements and helped test the app. Nick Aflitto and Julia Miller took photos for the website and tutorial respectively. 
