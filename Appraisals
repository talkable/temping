skipped_adapters = ENV["SKIPPED_ADAPTERS"].to_s.downcase
sqlite_skipped = skipped_adapters.include?("sqlite")
postgresql_skipped = skipped_adapters.include?("postgres")
mysql_skipped = skipped_adapters.include?("mysql")

appraise "activerecord-6.0" do
  gem "activerecord", "~> 6.0.0"
  gem "activesupport", "~> 6.0.0"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 1.4.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end

appraise "activerecord-6.1" do
  gem "activerecord", "~> 6.1.0"
  gem "activesupport", "~> 6.1.0"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 1.4.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end

appraise "activerecord-7.0" do
  gem "activerecord", "~> 7.0.0"
  gem "activesupport", "~> 7.0.0"
  gem "standard", "~> 1.31"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 1.6.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end

appraise "activerecord-7.1" do
  gem "activerecord", "~> 7.1.0"
  gem "activesupport", "~> 7.1.0"
  gem "standard", "~> 1.31"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 1.6.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end

appraise "activerecord-7.2" do
  gem "activerecord", "~> 7.2.0"
  gem "activesupport", "~> 7.2.0"
  gem "standard", "~> 1.31"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 2.0.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end

appraise "activerecord-8.0" do
  gem "activerecord", "~> 8.0.0"
  gem "activesupport", "~> 8.0.0"
  gem "standard", "~> 1.31"

  platforms :ruby, :truffleruby do
    gem "sqlite3", "~> 2.2.0" unless sqlite_skipped
    gem "pg", "~> 1.5.8" unless postgresql_skipped
    gem "mysql2", "~> 0.5.6" unless mysql_skipped
  end
end
