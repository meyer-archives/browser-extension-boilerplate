#!/bin/env ruby
# encoding: utf-8

# Extension shortname. a-z and underscores only.
EXT_NAME = 'browser-extension-boilerplate'

# Extension metadata displayed on the extensions page.
EXT_DISPLAY_NAME = 'Browser Extension Boilerplate'
EXT_DESC = IO.read('source/description.txt')
EXT_URL = 'https://github.com/meyer/browser-extension-boilerplate'
EXT_AUTHOR = 'Mike Meyer'

# Safari specific bundle ID.
EXT_BUNDLE_ID = 'fm.meyer.extbp'

# JS/Coffeescript files. Files are loaded sequentially.
EXT_FILES = ['jquery.js','demo.coffee']

# Allowed domains
EXT_WHITELIST = ['http:///*','https://*/*']
# Dimension of PNG Files in EXT_SOURCE_DIR with filename “Icon-##.png”.
# Can be 32, 48, 64, 96, or 128. 128 looks snazzy on retina displays.
EXT_ICONS = [48,128]

# Version number to bundle with the extension
@ext_version = '1.0'

# Source files relative to the project folder
EXT_SOURCE_DIR = './source'

# Chrome/Safari certificates required for extension signing.
EXT_CERT_DIR = '../certificates'

# Compiled extension filename without the file extension
EXT_BUILD_PREFIX = "#{EXT_NAME}-#{@ext_version}"

# Build destination
EXT_RELEASE_DIR = './bin'

# The extension’s files are rendered to this directory. It can be loaded with
# the Safari extension builder or in Chrome as an unpacked extension.
TEMP_DIR = './temp'

# Disable verbose output from fileutils commands
RakeFileUtils.verbose(false)

# The main deal.
load 'utils/helpers.rb'
load 'utils/build.rb'