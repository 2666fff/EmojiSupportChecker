# EmojiSupportChecker
check whether specific emoji support by current android os or not

for api >= 23 uses buildin method Paint.hasGlyph(string);
for api < 23 uses code from Googles Mozc project;

Usage: EmojiSupportChecker.getInstance().isRenderable(string);
