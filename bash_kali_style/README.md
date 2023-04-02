This is a shell customization inspired by the Kali Linux zsh config, re-made in a more minimalistic style. As you can see in the preview available in this folder, it's especially useful when navigating long paths to avoid asking yourself "what folder am I in, again?" every 5 minutes. Plus, it looks l33t, which is the most important feature.

---

**Step1:** Add the color variables you will find in the txt file in this folder to .bashrc in `/root/.bashrc` and the `~/.bashrc` in user home folders. You can add more colors or edit the example ones that you will already find

**Step2:** Choose one PS1 line to use and also add the line to the above files (the root one goes to `/root/.bashrc`, while user ones go, for example, in `/home/myname/.bashrc`. You can also do it in a more global way for all current and new users, if you prefer)

**Step3:** Do a `source ~/.bashrc` to apply settings immediately, or log out and back in

**Step4 (optional):** Customize the PS1 string further to your own taste (repeat step 3 every time you edit it)

---

To return to default settings, comment or remove all the lines you just added to `.bashrc` and leave `PS1` as is:

For normal users:
```
PS1="[\u@\h \W]\$ "
```
For root user:
```
PS1="[\u@\h \W]\# "
```

