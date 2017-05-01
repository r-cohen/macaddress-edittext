# MacAddressEditText
Android EditText component for handling mac address input format
## Installation
Add the JitPack repository to your root **Project** gradle file at the end of repositories:
```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add the dependency to the **Module** gradle file:
```gradle
	dependencies {
	        ...
          	compile 'com.github.phearme:MacAddressEditText:-SNAPSHOT'
	}
```
## Usage
```xml
    <com.phearme.macaddressedittext.MacAddressEditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />
```
