My current experimental keyboard layout.

---
files base.lst, evdev.lst(/usr/share/X11/xkb/rules)
  dvorak-fo       fo: Faroese (Dvorak of the north)
---
files base.xml, evdev.xml(/usr/share/X11/xkb/rules)
        <variant>
          <configItem>
            <name>dvorak-fo</name>
            <description>Faroese (Dvorak of the north)</description>
          </configItem>
        </variant>
---
in etc/default/keyboard
XKBLAYOUT="fo"
XKBVARIANT="dvorak-fo"
---
