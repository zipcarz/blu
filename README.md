blu
===
                     if (Integer.parseInt(a) < Integer.parseInt(min_frequency.getValue()))
429	429	                         return false;
430		-                } catch (NullPointerException e) {
430	+                } catch (NumberFormatException e) {
431	431	                     return false;
432	432	                 }
433	433	 
...	...	@@ -456,7 +456,7 @@ public boolean onPreferenceChange(Preference preference, Object o) {
456	456	                 try {
457	457	                     if (Integer.parseInt(a) > Integer.parseInt(max_frequency.getValue()))
458	458	                         return false;
459		-                } catch (NullPointerException e) {
459	+                } catch (NumberFormatException e) {
460	460	                     return false;
461	461	                 }
