# Windows-Startmenu-Creator-Tool
<!-- wp:paragraph {"fontSize":"normal"} -->
<p class="has-normal-font-size">Creating startmenues for Windows could be a complex task as it requires us to export and customize an XML-file to get it right. It get's even more complex if we want to customize the taskbar as well.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"normal"} -->
<p class="has-normal-font-size">This is where the Windows Startmenu Creator Tool comes to play. The tool will help us export the XML from a reference device and will ease the taskbar customization process by a lot... it will even connect to MEM, upload the XML and create the policy for you, how awesome is that?! 😍</p>
<!-- /wp:paragraph -->
<!-- wp:paragraph {"fontSize":"normal"} -->
<p class="has-normal-font-size">We have some prereqs to take into consideration:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true,"fontSize":"normal"} -->
<ol class="has-normal-font-size"><li>PowerShell execution policy must be set to allow the tool to run <a href="https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.2" target="_blank" rel="noreferrer noopener">about Execution Policies - PowerShell | Microsoft Docs</a></li><li>The PowerShell modue: Microsoft.Graph.Intune must be installed on the system running the tool <a href="https://github.com/microsoft/Intune-PowerShell-SDK" target="_blank" rel="noreferrer noopener">GitHub - microsoft/Intune-PowerShell-SDK: Native PowerShell support for invoking Microsoft Intune Graph API to enable IT Pro scenario automation.</a></li></ol>
<!-- /wp:list -->

<!-- wp:paragraph {"fontSize":"normal"} -->
<p class="has-normal-font-size">Now that we have taken care of the pre-reqs it is time to... wait for it... </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"medium"} -->
<p class="has-medium-font-size">....Rock Enroll<strong>!</strong></p>
<!-- /wp:paragraph -->
<!-- wp:paragraph {"fontSize":"normal"} -->
<p class="has-normal-font-size"><s>No support for Windows 11 as for now. I will work on that!</s><br>Edit: Good news! support for Windows 11 has been added.</p>
<!-- /wp:paragraph -->

<!-- wp:table {"hasFixedLayout":true,"className":"is-style-regular"} -->
<figure class="wp-block-table is-style-regular"><table class="has-fixed-layout"><tbody><tr><td>Windows 10</td><td>OK</td></tr><tr><td>Windows 11</td><td>OK</td></tr></tbody></table></figure>
<!-- /wp:table -->
The tool in action:<br>
![W11 support - Long](https://user-images.githubusercontent.com/74212904/150674305-0b75f748-cac2-4ad8-a67a-c50504406123.gif)
