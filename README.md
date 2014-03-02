=pod

=head1 NAME

logcat_format - pretty print android adb logcat output

=head1 DESCRIPTION

A tool to pretty print the output of the android sdk 'adb logcat' command.

Before 

=begin HTML

<p><img src="http://gphat.github.com/chart-clicker/static/images/examples/line.png"
width="500" height="250" alt="Line Chart" /></p>

=end HTML

After

=begin HTML

<p><img src="http://gphat.github.com/chart-clicker/static/images/examples/line.png"
width="500" height="250" alt="Line Chart" /></p>

=end HTML

=head1 SYNOPSIS

Default adb logcat pretty print ..

    % logcat_format 

For default logcat output for emulator only ..

    % logcat_format -e 

For default logcat output for device only ..

    % logcat_format -d

For other adb logcat commands, just pipe into logcat_format ..

    % adb logcat -v threadtime | logcat_format
    % adb -e logcat -v process | logcat_format

=head1 VERSION

version 0.03

=cut
