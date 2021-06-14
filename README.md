# Install
git clone https://github.com/viper0670/Neptune-ddoser.git

 # Usage
 
USAGE: ./neptune.py <url> [OPTIONS]')
     OPTIONS:
     -u, --useragents File with user-agents to use\(default: randomly generated)')
     -w, --workers\t\tNumber of concurrent workers\(default: {0})'.format(DEFAULT_WORKERS))
     -s, --sockets\t\tNumber of concurrent sockets\t\t\t\t(default: {0})'.format(DEFAULT_SOCKETS))
     -m, --method\t\tHTTP Method to use \'get\' or \'post\'  or \'random\'\t\t(default: get)')
     -n, --nosslcheck\tDo not verify SSL Certificate\t\t\t\t(default: True)')
     -d, --debug\t\tEnable Debug Mode [more verbose output]\t\t\t(default: False)')
     -h, --help\t\tShows this help')
