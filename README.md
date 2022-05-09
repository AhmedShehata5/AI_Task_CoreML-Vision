# AI_Task_CoreML-Vision
Crop and scale photos using the Vision framework and classify them with a Core ML model.
The app identifies the most prominent object in an image by using MobileNet, an open source image classifier model that recognizes around 1,000 different categories.

Each time a user selects a photo from the library or takes a photo with a camera, the app passes it to a Vision image classification request. Vision resizes and crops the photo to meet the MobileNet model’s constraints for its image input, and then passes the photo to the model using the Core ML framework behind the scenes. Once the model generates a prediction, Vision relays it back to the app, which presents the results to the user.

Team Members:
▪️احمد شحاتة رسمي محمد شريف  سكشن 2
▪️عبدالله صلاح عطيه خليل  سكشن 8
▪️سمير مجدي اسحاق يعقوب  سكشن 7 

Emails:
▪️ahmedrasmy@std.mans.edu.eg
▪️Abdallah774@std.mans.edu.eg
▪️samirmagdy@std.mans.edu.eg
