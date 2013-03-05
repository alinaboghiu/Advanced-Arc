CXXFLAGS = -O3 -Wall -Wno-deprecated -I/usr/include/vtk-5.6

OBJS = ACA2-2013.o Mesh.o Smooth.o SVD2x2.o

LIBS = -L/usr/lib/vtk-5.6 -lvtkIO -lvtkFiltering -lvtkCommon

TARGET = ACA2-2013

$(TARGET):	$(OBJS)
	@$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	@$(TARGET)

clean:
	@rm -f $(OBJS) $(TARGET)
