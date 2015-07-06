# The Project is moved to github. https://github.com/snowdream/51-android #




51-android.rules:
> git clone https://code.google.com/p/51-android/


INSTALL

1.Copy the file "51-android.rules" to "/etc/udev/rules.d/51-android.rules".To Achieve it，You should be sure that you have the root permission.

2.Now open the console,and execute:
sudo chmod a+r /etc/udev/rules.d/51-android.rules

3.Then execute：
sudo service udev restart


4.When plugged in over USB, can verify that your device is connected by executing `adb devices` from your SDK platform-tools/ directory. If connected, you'll see the device name listed as a "device."