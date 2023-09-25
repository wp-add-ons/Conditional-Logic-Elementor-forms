# Conditional-Logic-Elementor-forms
with Conditional logic will take your form to the next level by allowing you to produce intelligent forms that satisfy your users and drive the results you’re looking for.

**Table of contents:**

What is Conditional Logic?  
How to Apply Conditional Logic in WordPress Forms?  
Simple Conditional Logic  
Complex Conditional Logic  
Wrapping up  
Related Doc

## What is Conditional Logic?
Conditional logic is a feature in form-building tools, that allows you to create dynamic and interactive forms based on certain conditions or user input. It enables you to control the behavior and visibility of form elements, such as fields, sections, or even entire form elements, depending on specific rules or criteria.

![Image](https://lh4.googleusercontent.com/pEBEI_BL0F3c7eUeIpHXmnOgSfccU9oozozK0RfgG87OFjX6KkAnvfnAbQ1eJptbDH8HCnhH2uLIcxRD3vbndB9lxkbg0oavEVl5e6HJBRMR7nUwGVcoKXf2ZD-v7Kw0LN1lHDzlfCZdMf4i8yZ9Tqc)

It’s a process that says “If X, then do Y, but if Z then do W”.

For example, let’s say you have a form that collects information for a conference registration. You can use conditional logic to show different sets of fields based on the user’s selection of attendee type (e.g., speaker, attendee, sponsor). If the user selects “speaker,” additional fields related to speaker details can be dynamically displayed. If they select “attendee,” a different set of fields for attendee information can be shown. This way, the form adapts and presents the relevant fields based on the user’s choice.

## How to Apply Conditional Logic in WordPress Forms?
You need to create a new form and check on the Enable Conditional Logic option on any field to imply conditional logic on that field.

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-133.png)

## Simple Conditional Logic
The most common use of conditional logic is to show or hide fields depending on what the user selects. This is often called the **IF/THEN** condition.

For example, If your form asks the user if they want to be contacted, a field for their email address shows if they check the **“Yes”** checkbox.

![Image](https://add-ons.org/wp-content/uploads/2023/09/conditional-logic-elementor.gif)

* Step 1: Set up your fields. As we will be using a checbox to handle the display of two selections: Yes. Of course/ No. Please do not contact me.

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-136.png)

* Step 2: As we want **Email** to show up when **Yes. Of course** is selected, we will need to Enable conditional logic on **Email.** Open it by clicking on the field, and click on **Enable Conditional Logic** section. Then set the condition: **contact123 is Yes. Of course**

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-135.png)

where:

contact123: ID Field of Would you like to be contacted?

After you save the form, it will apply conditional logic based on user interaction.

## Complex Conditional Logic
In some cases, you can discover that one single conditional logic isn’t complex enough. You can include as many conditions as you want, though. Complex conditional logic is also known as the **AND/OR** condition.

+ AND: Affects the field if and only if all of the conditions are met 

+ OR: Affects the field if only one of the conditions is met

For example, This is an example of AND Conditional logic. Here, **Email Confirmation!** Field shows only if both the conditions  **Yes. That’s sound great** AND **Program is ticked.**

![Image](https://add-ons.org/wp-content/uploads/2023/09/conditional-logic-1-elementor.gif)

* Step 1: Set up your fields. As we will be using a radio to handle the display of various selections: Yes. That’s sound great/ No. Thanks

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-137.png)

* Step 2: Using a radio to handle the display of two selections:

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-138.png)

* Step 3: We want Email Confirmation to show up when Yes. That’s sound great AND Program are selected, we will need to enable conditional logic on Email Confirmation. Open it by clicking on the field, and clicking on the **Enable Conditional Logic** section.
* Step 4: Set conditions: at Email Confirmation field
field_6c99974 is Yes. That’s sound great AND field_b96d13a not empty

where:

field_6c99974: ID of Would you like to join our Talk Shows?

field_b96d13a: ID of Program

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-139.png)

![Image](https://add-ons.org/wp-content/uploads/2023/09/image-140.png)

* Step 5: Save and have a preview of the user interaction
## Wrapping up

By utilizing Elementor’s Form Conditional Logic, you can create dynamic and interactive forms that adjust based on user input or predefined conditions. This feature allows you to provide a more personalized and streamlined experience for form users while capturing the necessary information efficiently.

I hope you will use this process to make a user-friendly [Elementor conditional logic](https://1.envato.market/danq22)form in your WordPress website.
