#Overview

This is a repo of chef cookbooks for managing Riverbed's Stingray Traffic
Manager. The philosophy of this implementation is that chef should be the thing
that replicates config, and not the admin server.  So, you will observe that the
providers will generally write files directly, and the values that get written
into each file come from node attributes.

#Cookbooks

##stingray

###resources

####stingray

###providers

####stingray90

####stingray90r2

###recipes

###templates

###files

#Other Resources

##Official Documentation

##Live Users

###RightScale

The Riverbed&reg; Stingray Traffic Manager&trade; series ServerTemplates&reg; on
RightScale&trade; makes extensive use of this cookbook.  [A Free Developer
Edition](https://my.rightscale.com/library/server_templates/Stingray-Free-Developer-Editio/lineage/15764)
is available for anyone who wants to try all of the features of Stingray
in a non-production environment (subject to the terms specified in the
applicable end-user license agreements).  There are also a number of
ServerTemplates available that can be paid for by-the-hour.
