%hook SpringBoard

-(void)applicationDidFinishLaunching:(id)application {
%orig;
UIAlertView *alert = [[UIAlertView alloc] init];
alert.title = @”Hi,this is my repo”;
alert.message = @”i'm øwl4cce.Tweaks developer from 🇯🇵.”;
}
%end
