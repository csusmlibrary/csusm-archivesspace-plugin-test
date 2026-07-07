# csusm-archivesspace-plugins
(1) Lyrasis expects many clients to host their plugin code in public GitHub repositories, which they can pull from and deploy. (2) The client owns and maintains the plugin code over time.

# CSUSM ArchivesSpace Plugins

This repository contains custom plugins for the CSUSM ArchivesSpace instance.

## Plugins
- csusm_branding
  - Provides UI branding and customization for the public interface
  - Compatible with ArchivesSpace v4.1.1

## Notes
- Maintained by LTID (Library Technology Initiatives and Development)
- Used for Lyrasis-hosted ArchivesSpace deployment

## Relationship between csusm-archivesspace-plugin-test, csusm-archivesspace-plugins (plural), and csusm-archivesspace-plugin
- https://github.com/csusmlibrary/csusm-archivesspace-plugins (plural) was renamed to https://github.com/csusmlibrary/csusm-archivesspace-plugin-test, which still has the structure your_working_dir/csusm_branding/public
- https://github.com/csusmlibrary/csusm-archivesspace-plugin (singular) is a new repository that has the structure your_working_dir/public .
- The your_working_dir/public structure works better for Lyrasis, but I am keeping csusm_branding/public and therefore csusm-archivesspace-plugin-test, because csusm-archivesspace-plugin-test has a history of commits that illustrate how we trimmed down our original plugin.


