# PasswordEditText
Custom EditTextView to show/hide password with customizable icon.

<img width="270" src="./art/Screenshot.png" />

# How to use

```groovy
 <in.anshul.libray.PasswordEditText
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            app:hide_drawable="@drawable/hide_password"
            app:password_visible="true"
            android:hint="Confirm password"
            app:show_drawable="@drawable/show_password" />
```

# Customise
 
 * `app:show_drawable="@drawable/ic_custom_show"` 
 * `app:hide_drawable="@drawable/ic_custom_hide"`
 
Defualt Password Visiblity can be set using attr 
* `app:password_visible="true"`


[![](https://jitpack.io/v/anshulagarwal06/PasswordEditText.svg)](https://jitpack.io/#anshulagarwal06/PasswordEditText)


# Download

Include `jitpack.io` inside of **root** project `build.gradle`:

```groovy
allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
```

After that you can easily include the library in your **app** `build.gradle`:

```groovy
dependencies {
	        compile 'com.github.anshulagarwal06:PasswordEditText:v0.1'
	}
```

That's it build your project.
