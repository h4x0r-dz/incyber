<div dir="rtl" align='right'>

## Defense Evasion التهرب من الاكتشاف


### لتحميل بصيغ متعددة تفضل:
- صيغة JSON :[تفضل هنا]() 
- صيغة XLS :[تفضل هنا]()
- صيغة CSV :[تفضل هنا]() 
- صيغة XML :[تفضل هنا]()
- صيغة SQL :[تفضل هنا]()
- صيغة YML :[تفضل هنا]()
 
### التقنيات / Techniques
| ID / المعرف | المعرف الفرعي | الاسم/ Name                                                                                        | الوصف / Description |
|-------------|---------------|----------------------------------------------------------------------------------------------------|---------------------|
| T1548       |               | اساءة استخدام ميزة رفع الصلاحيات / Abuse Elevation Control Mechanism	                              |                     |
| T1548       | .001          | Setuid and Setgid                                                                                  |                     |
| T1548       | .002          | تخطي صلاحيات التحكم بالحسابات / Bypass User Account Control	                                       |                     |
| T1548       | .003          | Sudo and Sudo Caching                                                                              |                     |
| T1548       | .004          | Elevated Execution with Prompt                                                                     |                     |
| T1134       |               | التلاعب بالتوكن / Access Token Manipulation                                                        |                     |
| T1134       | .001          | Token Impersonation/Theft                                                                          |                     |
| T1134       | .002          | Create Process with Token                                                                          |                     |
| T1134       | .003          | Make and Impersonate Token                                                                         |                     |
| T1134       | .004          | Parent PID Spoofing                                                                                |                     |
| T1134       | .005          | SID-History Injection                                                                              |                     |
| T1197       |               | BITS Jobs                                                                                          |                     |
| T1140       |               | فك الترميز من الملفات او المعلوماتDeobfuscate/Decode Files or Information                          |                     |
| T1006       |               | الوصول المباشر للقرص / Direct Volume Access                                                        |                     |
| T1484       |               | Domain Policy Modification                                                                         |                     |
| T1484       | .001          | Group Policy Modification                                                                          |                     |
| T1484       | .002          | Domain Trust Modification                                                                          |                     |
| T1480       |               | Execution Guardrails                                                                               |                     |
| T1480       | .001          | Environmental Keying                                                                               |                     |
| T1211       |               | Exploitation for Defense Evasion                                                                   |                     |
| T1222       |               | File and Directory Permissions Modification                                                        |                     |
| T1222       | .001          | تعديل صلاحيات الملفات والمجلدات للويندوز / Windows File and Directory Permissions Modification     |                     |
| T1222       | .002          | تعديل صلاحيات الملفات والمجلدات لينكس  / Linux and Mac File and Directory Permissions Modification |                     |
| T1564       |               | اخفاء الادلة / Hide Artifacts                                                                      |                     |
| T1564       | .001          | اخفاء الملفات او المجلدات / Hidden Files and Directories                                           |                     |
| T1564       | .002          | اخفاء المستخدمين / Hidden Users                                                                    |                     |
| T1564       | .003          | اخفاء النوافذHidden Window                                                                         |                     |
| T1564       | .004          | NTFS File Attributes                                                                               |                     |
| T1564       | .005          | اخفاء ملفات النظام / Hidden File System                                                            |                     |
| T1564       | .006          | Run Virtual Instance                                                                               |                     |
| T1564       | .007          | VBA Stomping                                                                                       |                     |
| T1574       |               | Hijack Execution Flow                                                                              |                     |
| T1574       | .001          | DLL Search Order Hijacking                                                                         |                     |
| T1574       | .002          | DLL Side-Loading                                                                                   |                     |
| T1574       | .004          | Dylib Hijacking                                                                                    |                     |
| T1574       | .005          | Executable Installer File Permissions Weakness                                                     |                     |
| T1574       | .006          | LD_PRELOAD                                                                                         |                     |
| T1574       | .007          | Path Interception by PATH Environment Variable                                                     |                     |
| T1574       | .008          | Path Interception by Search Order Hijacking                                                        |                     |
| T1574       | .009          | Path Interception by Unquoted Path                                                                 |                     |
| T1574       | .010          | Services File Permissions Weakness                                                                 |                     |
| T1574       | .011          | Services Registry Permissions Weakness                                                             |                     |
| T1574       | .012          | COR_PROFILER                                                                                       |                     |
| T1562       |               | Impair Defenses                                                                                    |                     |
| T1562       | .001          | ادوات تعديل وتعطيل / Disable or Modify Tools                                                       |                     |
| T1562       | .002          | تعطيل مسجل الاحداث في الويندوز / Disable Windows Event Logging                                     |                     |
| T1562       | .003          | Impair Command History Logging                                                                     |                     |
| T1562       | .004          | تعديل او تعطيل انظمة جدران الحماية / Disable or Modify System Firewall                             |                     |
| T1562       | .006          | Indicator Blocking                                                                                 |                     |
| T1562       | .007          | تعديل او تعطيل جدران الحماية للخدمات السحابيةDisable or Modify Cloud Firewall                      |                     |
| T1562       | .008          | تعطيل السجلات للخدمات الحسابية / Disable Cloud Logs                                                |                     |
| T1070       |               | Indicator Removal on Host                                                                          |                     |
| T1070       | .001          | مسح السجلات من نظام ويندوز/ Clear Windows Event Logs                                               |                     |
| T1070       | .002          | مسج السجلات من نظام لينكس وماكClear Linux or Mac System Logs                                       |                     |
| T1070       | .003          | مسج سجل الاحداث من / Clear Command History                                                         |                     |
| T1070       | .004          | مسح الملفات / File Deletion                                                                        |                     |
| T1070       | .005          | مسح الارتباط والاتصال بملفات المشاركة / Network Share Connection Removal                           |                     |
| T1070       | .006          | Timestomp                                                                                          |                     |
| T1202       |               | Indirect Command Execution                                                                         |                     |
| T1036       |               | Masquerading                                                                                       |                     |
| T1036       | .001          | Invalid Code Signature                                                                             |                     |
| T1036       | .002          | Right-to-Left Override                                                                             |                     |
| T1036       | .003          | Rename System Utilities                                                                            |                     |
| T1036       | .004          | Masquerade Task or Service                                                                         |                     |
| T1036       | .005          | Match Legitimate Name or Location                                                                  |                     |
| T1036       | .006          | Space after Filename                                                                               |                     |
| T1556       |               | تعديل طريقة وعملية التحقق / Modify Authentication Process                                          |                     |
| T1556       | .001          | Domain Controller Authentication                                                                   |                     |
| T1556       | .002          | Password Filter DLL                                                                                |                     |
| T1556       | .003          | Pluggable Authentication Modules                                                                   |                     |
| T1556       | .004          | التحقق بواسطة اجهزة الشبكة / Network Device Authentication                                         |                     |
| T1578       |               | Modify Cloud Compute Infrastructure                                                                |                     |
| T1578       | .001          | انشاء نسخة / Create Snapshot                                                                       |                     |
| T1578       | .002          | انشاء نسخة للخدمات السحابية / Create Cloud Instance                                                |                     |
| T1578       | .003          | مسح الخدمات السحابية / Delete Cloud Instance                                                       |                     |
| T1578       | .004          | استعادة الخدمات السحابية / Revert Cloud Instance                                                   |                     |
| T1112       |               | تعديل الريجستري / Modify Registry                                                                  |                     |
| T1601       |               | تعديل  نسخة النظام / Modify System Image                                                           |                     |
| T1601       | .001          | سد الثغرات لنسخة النظام / Patch System Image                                                       |                     |
| T1601       | .002          | Downgrade System Image                                                                             |                     |
| T1599       |               | حدود البوابة الشبكية / Network Boundary Bridging                                                   |                     |
| T1599       | .001          | Network Address Translation Traversal                                                              |                     |
| T1027       |               | تشفير الملفات و المعلومات / Obfuscated Files or Information                                        |                     |
| T1027       | .001          | Binary Padding                                                                                     |                     |
| T1027       | .002          | Software Packing                                                                                   |                     |
| T1027       | .003          | Steganography                                                                                      |                     |
| T1027       | .004          | Compile After Delivery                                                                             |                     |
| T1027       | .005          | Indicator Removal from Tools                                                                       |                     |
| T1542       |               | Pre-OS Boot                                                                                        |                     |
| T1542       | .001          | النظام الثابت / System Firmware                                                                    |                     |
| T1542       | .002          | Component Firmware                                                                                 |                     |
| T1542       | .003          | Bootkit                                                                                            |                     |
| T1542       | .004          | ROMMONkit                                                                                          |                     |
| T1542       | .005          | TFTP Boot                                                                                          |                     |
| T1055       |               | حقن العمليات / Process Injection                                                                   |                     |
| T1055       | .001          | Dynamic-link Library Injection                                                                     |                     |
| T1055       | .002          | Portable Executable Injection                                                                      |                     |
| T1055       | .003          | Thread Execution Hijacking                                                                         |                     |
| T1055       | .004          | Asynchronous Procedure Call                                                                        |                     |
| T1055       | .005          | Thread Local Storage                                                                               |                     |
| T1055       | .008          | Ptrace System Calls                                                                                |                     |
| T1055       | .009          | Proc Memory                                                                                        |                     |
| T1055       | .011          | Extra Window Memory Injection                                                                      |                     |
| T1055       | .012          | Process Hollowing                                                                                  |                     |
| T1055       | .013          | Process Doppelgänging                                                                              |                     |
| T1055       | .014          | VDSO Hijacking                                                                                     |                     |
| T1207       |               | Rogue Domain Controller                                                                            |                     |
| T1014       |               | Rootkit                                                                                            |                     |
| T1218       |               | Signed Binary Proxy Execution                                                                      |                     |
| T1218       | .001          | تكوين مف HTML / Compiled HTML File                                                                 |                     |
| T1218       | .002          | لوحة التحكم / Control Panel                                                                        |                     |
| T1218       | .003          | CMSTP                                                                                              |                     |
| T1218       | .004          | InstallUtil                                                                                        |                     |
| T1218       | .005          | Mshta                                                                                              |                     |
| T1218       | .007          | Msiexec                                                                                            |                     |
| T1218       | .008          | Odbcconf                                                                                           |                     |
| T1218       | .009          | Regsvcs/Regasm                                                                                     |                     |
| T1218       | .010          | Regsvr32                                                                                           |                     |
| T1218       | .011          | Rundll32                                                                                           |                     |
| T1218       | .012          | Verclsid                                                                                           |                     |
| T1216       |               | Signed Script Proxy Execution                                                                      |                     |
| T1216       | .001          | PubPrn                                                                                             |                     |
| T1553       |               | Subvert Trust Controls                                                                             |                     |
| T1553       | .001          | Gatekeeper Bypass                                                                                  |                     |
| T1553       | .002          | Code Signing                                                                                       |                     |
| T1553       | .003          | SIP and Trust Provider Hijacking                                                                   |                     |
| T1553       | .004          | Install Root Certificate                                                                           |                     |
| T1221       |               | Template Injection                                                                                 |                     |
| T1205       |               | Traffic Signaling                                                                                  |                     |
| T1205       | .001          | Port Knocking                                                                                      |                     |
| T1127       |               | Trusted Developer Utilities Proxy Execution                                                        |                     |
| T1127       | .001          | MSBuild                                                                                            |                     |
| T1535       |               | Unused/Unsupported Cloud Regions                                                                   |                     |
| T1550       |               | Use Alternate Authentication Material                                                              |                     |
| T1550       | .001          | Application Access Token                                                                           |                     |
| T1550       | .002          | Pass the Hash                                                                                      |                     |
| T1550       | .003          | Pass the Ticket                                                                                    |                     |
| T1550       | .004          | Web Session Cookie                                                                                 |                     |
| T1078       |               | حساب فعال / Valid Accounts                                                                         |                     |
| T1078       | .001          | حساب افتراضي / Default Accounts                                                                    |                     |
| T1078       | .002          | حساب مدير النظام / Domain Accounts                                                                 |                     |
| T1078       | .003          | حساب محلي / Local Accounts                                                                         |                     |
| T1078       | .004          | حساب الخدمات الحسابية / Cloud Accounts                                                             |                     |
| T1497       |               | Virtualization/Sandbox Evasion                                                                     |                     |
| T1497       | .001          | فحص النظام / System Checks                                                                         |                     |
| T1497       | .002          | User Activity Based Checks                                                                         |                     |
| T1497       | .003          | Time Based Evasion                                                                                 |                     |
| T1600       |               | التشفير الضعيف / Weaken Encryption                                                                 |                     |
| T1600       | .001          | Reduce Key Space                                                                                   |                     |
| T1600       | .002          | Disable Crypto Hardware                                                                            |                     |
| T1220       |               | XSL Script Processing                                                                              |                     |


</div>
