IOS-Check-Network-Status-
=========================
Step 1: Download the library from following link.

Step 2: Create new project & Import  SystemConfiguration.framework into your project

Step 3: #import "CheckNetworkAvaliblity.h" in your main view controller or else anywhere you need.

Step 4: Call this method [CheckNetworkAvaliblity CheckNetwork]

Eg:
 - (void)viewDidLoad
{
    [super viewDidLoad];
    
    if ([CheckNetworkAvaliblity CheckNetwork])
    {
        NSLog(@"Success, Your network is available");
    }
    else
    {
        NSLog(@"Sorry, Network connection is unavailable");
    }
}


Happy Coding :-) 
Get more sample from http://Techdevmobile.com
