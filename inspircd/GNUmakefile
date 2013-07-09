CXXFLAGS = -pipe -DPIC -fPIC -fstack-protector-all -Wstack-protector --param ssp-buffer-size=1 -Wl,-z,relro -Wl,-z,now -D_FORTIFY_SOURCE=2 -O2
LDLIBS = -pthread -lstdc++
LDFLAGS =
CORELDFLAGS = -rdynamic -pie -L. $(LDFLAGS)
PICLDFLAGS = -fPIC -shared -rdynamic $(LDFLAGS)
