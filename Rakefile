require "yast/rake"

Yast::Tasks.submit_to :sle15sp4

Yast::Tasks.configuration do |conf|
  #lets ignore license check for now
  conf.skip_license_check << /.*/
  conf.obs_sr_project = "SUSE:SLE-15-SP4:Update:Products:Micro53"
end
