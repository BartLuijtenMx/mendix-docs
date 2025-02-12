---
title: "Using Eclipse"
url: /refguide7/using-eclipse/

---

## 1 Introduction

Using Eclipse to write and debug the Java actions in your Mendix project is really easy. When the Mendix model is deployed, an Eclipse project file, classpath file, and launch configuration are generated.

In Mendix, all text is saved in UTF-8 encoding. First make sure your source code is also saved in UTF-8\. This can be done by going to the window menu and selecting preferences, then selecting UTF-8 as shown in the screenshot below.

{{% alert color="info" %}}
{{< figure src="/attachments/refguide7/java-programming/using-eclipse/918120.png" class="no-border" >}}
Settings UTF-8 encoding.
{{% /alert %}}

## 2 Prerequisites

You should also have a Java Development Kit (JDK) installed and selected.

{{% alert color="info" %}}
{{< figure src="/attachments/refguide7/java-programming/using-eclipse/918186.png" class="no-border" >}}
Selecting a default JDK.
{{% /alert %}}

Make sure you add a JDK and select it as the default in Eclipse.

## 3 Procedure

To add a Mendix project to Eclipse, you can perform these steps:

1. Open the **File** menu and click **Import**.
2. Open the **General** folder and select **Existing projects into Workspace** and click **Next**.
3. Use the option **Select root directory**, browse to your Mendix project folder and click **Finish**.

{{% alert color="info" %}}

{{< figure src="/attachments/refguide7/java-programming/using-eclipse/917580.png" class="no-border" >}}
Import existing project.

{{% /alert %}}{{% alert color="info" %}}
{{< figure src="/attachments/refguide7/java-programming/using-eclipse/917527.png" class="no-border" >}}
Import existing project step 2.
{{% /alert %}}

Now you can happily start editing your Java actions as you would do normally.

To actually launch the project, go to 'debug configurations' or 'run configurations' depending on how you'd like to run the project. On the left-side menu, select the 'Java application' menu and you'll see a launch configuration generated by the Mendix Desktop Modeler. Simply click 'debug' or 'run' on your right to start the application.

{{% alert color="info" %}}
{{< figure src="/attachments/refguide7/java-programming/using-eclipse/917586.png" class="no-border" >}}
Looking up your launch configuration.
{{% /alert %}}

After you have launched the application, you will see the M2EE admin console popup. This is the same console as you would normally see in the Mendix Desktop Modeler if you would run the project from there. You can stop your application by closing the console.

{{% alert color="info" %}}
{{< figure src="/attachments/refguide7/java-programming/using-eclipse/917582.png" class="no-border" >}}
The M2EE admin console.
{{% /alert %}}
