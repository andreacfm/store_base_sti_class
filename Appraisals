RAILS_VERSIONS = [
	"3.0.5",
	"3.0.6",
	"3.0.7",
	"3.0.8",
	"3.0.9",
	"3.0.10",
	"3.0.11",
	"3.0.12",
	"3.1.0",
	"3.1.2",
	"3.1.3",
	"3.1.4",
	"3.2.0",
	"3.2.1",
	"3.2.2",
	"3.2.3"
]

RAILS_VERSIONS.each do |version|
  appraise "rails_#{version}" do
    gem "activerecord", version
  end
end

