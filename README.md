med-interaction
===============

Custom solution to allow for NextGen's office procedure templates to perform med interactions.

How to integrate this change:
1.	Import the 2 templates that start with ngkbm_ (ngkbm_med_inter_config and ngkbm_med_interaction).
2.	Integrate the necessary triggers to fire the interaction checking
	a.	Use triggers to your version of the Office Px template (triggers.png) OR 
	b.	Use the provided KBM 8.0 or KBM 8.3 templates with only this change included.
3.	Configure the practice template with the desired preferences (2 radio buttons at the top).
4.	Add the medication name, CPT code (from the Office Px picklists) and the NDC ID that should be used for the interaction check.


dose-calculation
===============
1. Import the Office_Px_NXT842 template or extract the stored procedure, appdev_dose_inj, and manually install it
2. Integrate the necessary triggers to fire the dose calculation

![Dose calculation triggers](https://github.com/kevinfosterNG/med-interaction/blob/master/unit_conversion.jpg)