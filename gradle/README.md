# Gradle Basic Commands

# CLI Options 

	USAGE: gradle [option...] [task...]

	-?, -h, --help            Shows this help message.
	-a, --no-rebuild          Do not rebuild project dependencies.
	-b, --build-file          Specify the build file.
	--build-cache             Enables the Gradle build cache. Gradle will try to reuse outputs from previous builds.
	-c, --settings-file       Specify the settings file.
	--configure-on-demand     Configure necessary projects only. Gradle will attempt to reduce configuration time for large multi-project builds. [incubating]
	--console                 Specifies which type of console output to generate. Values are 'plain', 'auto' (default), 'rich' or 'verbose'.
	--continue                Continue task execution after a task failure.
	-D, --system-prop         Set system property of the JVM (e.g. -Dmyprop=myvalue).
	-d, --debug               Log in debug mode (includes normal stacktrace).
	--daemon                  Uses the Gradle Daemon to run the build. Starts the Daemon if not running.
	--foreground              Starts the Gradle Daemon in the foreground.
	-g, --gradle-user-home    Specifies the gradle user home directory.
	-I, --init-script         Specify an initialization script.
	-i, --info                Set log level to info.
	--include-build           Include the specified build in the composite.
	-m, --dry-run             Run the builds with all task actions disabled.
	--max-workers             Configure the number of concurrent workers Gradle is allowed to use.
	--no-build-cache          Disables the Gradle build cache.
	--no-configure-on-demand  Disables the use of configuration on demand. [incubating]
	--no-daemon               Do not use the Gradle daemon to run the build. Useful occasionally if you have configured Gradle to always run with the daemon by default.
	--no-parallel             Disables parallel execution to build projects.
	--no-scan                 Disables the creation of a build scan. For more information about build scans, please visit https://gradle.com/build-scans.
	--offline                 Execute the build without accessing network resources.
	-P, --project-prop        Set project property for the build script (e.g. -Pmyprop=myvalue).
	-p, --project-dir         Specifies the start directory for Gradle. Defaults to current directory.
	--parallel                Build projects in parallel. Gradle will attempt to determine the optimal number of executor threads to use.
	--priority                Specifies the scheduling priority for the Gradle daemon and all processes launched by it. Values are 'normal' (default) or 'low' [incubating]
	--profile                 Profile build execution time and generates a report in the <build_dir>/reports/profile directory.
	--project-cache-dir       Specify the project-specific cache directory. Defaults to .gradle in the root project directory.
	-q, --quiet               Log errors only.
	--refresh-dependencies    Refresh the state of dependencies.
	--rerun-tasks             Ignore previously cached task results.
	-S, --full-stacktrace     Print out the full (very verbose) stacktrace for all exceptions.
	-s, --stacktrace          Print out the stacktrace for all exceptions.
	--scan                    Creates a build scan. Gradle will emit a warning if the build scan plugin has not been applied. (https://gradle.com/build-scans)
	--status                  Shows status of running and recently stopped Gradle Daemon(s).
	--stop                    Stops the Gradle Daemon if it is running.
	-t, --continuous          Enables continuous build. Gradle does not exit and will re-execute tasks when task file inputs change.
	--update-locks            Perform a partial update of the dependency lock, letting passed in module notations change version. [incubating]
	-v, --version             Print version info.
	-w, --warn                Set log level to warn.
	--warning-mode            Specifies which mode of warnings to generate. Values are 'all', 'fail', 'summary'(default) or 'none'
	--write-locks             Persists dependency resolution for locked configurations, ignoring existing locking information if it exists [incubating]
	-x, --exclude-task        Specify a task to be excluded from execution.
