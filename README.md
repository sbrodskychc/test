<<<<<<< HEAD
# test
=======
# test
Final edit to README

# testcode
 use Data::Dumper;
 $Data::Dumper::Terse  = 1;
 $Data::Dumper::Indent = 0;
 $Data::Dumper::Pad = "\n";
 $Data::Dumper::Sortkeys = 1;
 my $sub_name = (caller(0))[3];
 use POSIX;
 open ( FHANDLE, ">>/sharedfs/tap/logs/stacey_debug.log" );
 print FHANDLE Dumper(strftime("%A %b %d %Y %I:%M:%S %p", localtime()) );
 print FHANDLE "\n\n# ";
 print FHANDLE __FILE__, '   line: ', __LINE__ ;                         
 print FHANDLE "\n\nRoutine: $sub_name\n\n# ";
 print FHANDLE "\n\n# ";
 print FHANDLE "\n\n\$sth: \n\n# ";
 print FHANDLE Dumper($sth);
 print FHANDLE "\n\n# ";
 close FHANDLE;               
>>>>>>> 8b1b797... Final edit to README
