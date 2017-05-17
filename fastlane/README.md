fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

## Choose your installation method:

<table width="100%" >
<tr>
<th width="33%"><a href="http://brew.sh">Homebrew</a></td>
<th width="33%">Installer Script</td>
<th width="33%">Rubygems</td>
</tr>
<tr>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS</td>
<td width="33%" align="center">macOS or Linux with Ruby 2.0.0 or above</td>
</tr>
<tr>
<td width="33%"><code>brew cask install fastlane</code></td>
<td width="33%"><a href="https://download.fastlane.tools">Download the zip file</a>. Then double click on the <code>install</code> script (or run it in a terminal window).</td>
<td width="33%"><code>sudo gem install fastlane -NV</code></td>
</tr>
</table>
# Available Actions
### update_podspec
```
fastlane update_podspec
```
Update template podspec with version and asset_url.
### deploy_podspec
```
fastlane deploy_podspec
```
Deploy podspec to the podspec repository.
### upload_assets
```
fastlane upload_assets
```
Upload assets to Github Release
### update_github_release
```
fastlane update_github_release
```
Update existing GitHub Release
### get_github_releases
```
fastlane get_github_releases
```
Get all GitHub Releases for repo
### get_latest_release
```
fastlane get_latest_release
```

### get_assets_list
```
fastlane get_assets_list
```
Get all assets for GitHub Releases
### delete_asset
```
fastlane delete_asset
```
Delete asset for GitHub Release
### get_release_by_tag
```
fastlane get_release_by_tag
```

### publish_release
```
fastlane publish_release
```

### sync_podspec
```
fastlane sync_podspec
```


----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
