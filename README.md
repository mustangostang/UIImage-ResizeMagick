UIImage-Resize
==============

This category allows you to resize an UIImage.

This category defines the following methods:
```objective-c
  - (UIImage *) resizedImageByWidth:  (NSUInteger) width;
  - (UIImage *) resizedImageByHeight: (NSUInteger) height;
  - (UIImage *) resizedImageWithMaximumSize: (CGSize) size;
  - (UIImage *) resizedImageWithMinimumSize: (CGSize) size;
````
Support for imageOrientation/EXIF orientation will be added in future versions.
