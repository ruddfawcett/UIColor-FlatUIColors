UIColor+FlatUIColors
====================

Simple UIColor category from flat ui colors found here: http://flatuicolors.com/.

##Use:
To use, just import the header, `UIColor+FlatUIColors.h`.  Then (because its a UIColor category) just use, for example:

```obj-c
UIView *view = [[UIView alloc] initWithFrame:self.view.bounds];
view.backgroundColor = [UIColor alizarinColor];
```


##Colors:

```obj-c
+ (instancetype)alizarinColor;
+ (instancetype)amethystColor;
+ (instancetype)asbestosColor;
+ (instancetype)belizeHoleColor;
+ (instancetype)carrotColor;
+ (instancetype)cloudsColor;
+ (instancetype)concreteColor;
+ (instancetype)emeraldColor;
+ (instancetype)greenSeaColor;
+ (instancetype)midnightBlueColor;
+ (instancetype)nephritisColor;
+ (instancetype)flatOrangeColor; // You have to add "flat" before "orange", because there is already a [UIColor orangeColor]
+ (instancetype)peterRiverColor;
+ (instancetype)pomegranateColor;
+ (instancetype)pumpkinColor;
+ (instancetype)silverColor;
+ (instancetype)sunFlowerColor;
+ (instancetype)turquoiseColor;
+ (instancetype)wetAsphaltColor;
+ (instancetype)wisteriaColor;
```