This is an example of a customization to add rendition definitions that
do more than just resizing, i.e. applying transformation filters.

It includes a `blur` rendition which resizes similar to the OOTB `imgpreview`
rendition definition, but also applies a blur filter.

See the [commandOptions property in the thumbnail defition](https://github.com/AlfrescoLabs/custom-transform-rendition/blob/master/src/main/amp/config/alfresco/module/custom-transform-rendition/module-context.xml#L35).