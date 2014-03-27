Spectrum Inspire Launcher Theme Sample
======================================

Creating a theme for Inspire Launcher is very easy. At the moment, you can theme:
icons, wallpaper, appdrawer icon, dock background, folder icon and page indicators. (More things to come)

For icons, follow the standard guidelines for NOVA, Apex etc icon packs.

For other things, just open the arrays.xml and follow my guidelines!

Don't forget to add the filter to your manifest to allows Inspire Launcher to detect your app as an Inspire theme:

            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <action android:name="com.bam.android.inspirelauncher.action.THEME" />
            </intent-filter>
            
Happy theming!
