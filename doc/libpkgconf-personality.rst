
libpkgconf `personality` module
=========================

.. c:function:: const pkgconf_cross_personality_t *pkgconf_cross_personality_default(void)

   Returns the default cross-compile personality.

   :rtype: pkgconf_cross_personality_t*
   :return: the default cross-compile personality

.. c:function:: pkgconf_cross_personality_t *pkgconf_cross_personality_find(const char *triplet)

   Attempts to find a cross-compile personality given a triplet.

   :rtype: pkgconf_cross_personality_t*
   :return: the default cross-compile personality
